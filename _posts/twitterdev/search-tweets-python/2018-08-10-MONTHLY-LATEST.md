---
layout: monthly-metrics-v0.1
title: TwiterOSS Metrics Report for twitterdev/search-tweets-python | MONTHLY-2018-08-10 | 2018-08-10
permalink: /twitterdev/search-tweets-python/MONTHLY/

owner: twitterdev
repo: search-tweets-python
reportID: MONTHLY-2018-08-10
datestampThisMonth: 2018-08-10
datestampLastMonth: 2018-07-13
---

<table style="width: 100%">
    <tr>
        <th>Metric</th>
        <th>This Month</th>
        <th>Last Month</th>
        <th>+/-</th>
    </tr>
    {% for item in site.data["twitterdev"]["search-tweets-python"]["MONTHLY-2018-08-10"]["data"] %}
    <tr>
        <th>{{ item[0] }}</th>
        <th>{{ item[1]["this_month"] }}</th>
        <th>{{ item[1]["last_month"] }}</th>
        <th>{{ item[1]["diff"] }}</th>
    </tr>
    {% endfor %}
</table>
