# https://github.com/frappe/helm/blob/5.0.49/erpnext/values.yaml#L16
ARG BASE_IMAGE=frappe/erpnext:v14.10.0
FROM ${BASE_IMAGE}
# add healthcare
RUN bench get-app healthcare
