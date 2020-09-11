+++
title = "Resources"
weight = 20
chapter = true
+++

{{<mermaid>}}
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section série à faire
        Completed task            :done,    des1, 2020-09-01, 2020-09-08
        Série 1               :active,  des2, 2020-09-01, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2020-09-01,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
{{< /mermaid >}}
