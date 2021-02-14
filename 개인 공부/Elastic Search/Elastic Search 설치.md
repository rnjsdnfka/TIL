## [Elastic Search설치](https://www.elastic.co/kr/downloads/elasticsearch)
- 압축 해제 후 bin/elasticsearch 실행후 http://localhost:9200 으로 확인
- 단일 노드로 이뤄진 일래스틱 클러스터 구성이 됨을 확인 할 수 있다.

```
## bin/elasticsearch 실행과 같다.
 /Users/user/Desktop/ES/elasticsearch-7.11.0/bin/elasticsearch; exit
```

```
$ curl http://localhost:9200
{
  "name" : "AL01705696.local",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "CchXhVWnRNaxsrM1eZvQ1g",
  "version" : {
    "number" : "7.11.0",
    "build_flavor" : "default",
    "build_type" : "tar",
    "build_hash" : "8ced7813d6f16d2ef30792e2fcde3e755795ee04",
    "build_date" : "2021-02-08T22:44:01.320463Z",
    "build_snapshot" : false,
    "lucene_version" : "8.7.0",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}
```

## [키바나 설치](https://www.elastic.co/downloads/kibana)
- 압축 해제 후 bin/kibana 실행후 http://localhost:5601 으로 확인
- 주의 bin/elasticsearch이 실행 되어있어야한다.
```  
## bin/kibana 실행과 같다.
$ /Users/user/Desktop/ES/kibana-7.11.0-darwin-x86_64/bin/kibana ; exit
```
