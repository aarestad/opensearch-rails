## 1.1.0
- Ruby 3.2 support
- Remove support for unsupported Ruby & Rails versions:
  - Rails >= 6.1
  - Ruby >= 2.7
- Ensure compatibility with opensearch-ruby 3

## 1.0.0

* Support OpenSearch 2 by removing deprecated type and include_type_name parameters

## 0.1.1

* Pin opensearch-ruby to '~> 1.1' because OpenSearch 2 is not supported yet

## 0.1.0

* Fork [elasticsearch-rails v7.2.1](https://github.com/elastic/elasticsearch-rails/tree/v7.2.1)
* Replace elasticsearch-ruby by opensearch-ruby
* Change Elasticsearch module name to OpenSearch
* Rename ELASTICSEARCH_URL environment variable to OPENSEARCH_URL
* Rename __elasticsearch__ method to __opensearch__

