---
layout: metrics-v0.1
title: TwiterOSS Metrics Report for twitter/fatcache | WEEKLY-2018-07-06 | 2018-07-06
permalink: /twitter/fatcache/WEEKLY.html

owner: twitter
repo: fatcache
reportID: WEEKLY-2018-07-06
datestampThisWeek: 2018-07-06
datestampLastWeek: 2018-06-29
---

<table style="width: 100%">
    <tr>
        <th>Metric</th>
        <th>This Week</th>
        <th>Last Week</th>
        <th>+/-</th>
    </tr>
    {% for item in site.data["twitter"]["fatcache"]["WEEKLY-2018-07-06"]["data"] %}
    <tr>
        <th>{{ item[0] }}</th>
        <th>{{ item[1]["this_week"] }}</th>
        <th>{{ item[1]["last_week"] }}</th>
        <th>{{ item[1]["diff"] }}</th>
    </tr>
    {% endfor %}
</table>
