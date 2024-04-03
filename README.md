# go_rss_aggregator_stripped_helm_chart

## Manually deployed resources
### Backend
A secret is necessary for the backend deployment. The secret is present in `manual/secret-backend.yaml` and it has to be in the same namespace as the backend deployment. The name has to be `go-rss-aggregator-stripped-backend` - as written in the YAML template.