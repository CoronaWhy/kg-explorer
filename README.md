# kg-explorer
CoronaWhy Knowledge Graph Explorer based on SPARQL queries. 

grlc API: http://grlc.io/api-git/CoronaWhy/kg-explorer#/default/get_keywordsOverview

Example SPARQL:
```
curl -X GET "http://grlc.io/api-git/CoronaWhy/kg-explorer/keywordsOverview?endpoint=https%3A%2F%2Ftriplestore.coronawhy.org%2Fvr%2Fsparql" -H "accept: text/csv"
```

Expected results:
```
keyword,keywordCount
media,68
virtual reality,30
vr headsets,8
vr headset,7
vr technology,6
augmented reality,5
global virtual,5
market size,5
reality program,5
virtual environments,5
virtual world,5
virtual worlds,5
vr training,5

```
