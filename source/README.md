### Source
This folder contains:

* an [`anomaly-detection`](./anomaly-detection) folder, which contains:
  1. a [`metrics`](./anomaly-detection/metrics) folder, which contains sample metric datasets:
      1. [`prometheus-route-aiops-prod-prometheus-predict-cloud.paas.psi.redhat.com`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com) should contain datasets for two metrics:
          1. [`badger_disk_reads:rate1m`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_reads:rate1m) which will contain mainly:
             1. [`1month of data (Aug 13-Sep 13)`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_reads:rate1m/1month%20of%20data%20(Aug%2013-Sep%2013)) - This contains 1 month of metric data collected for Dgraph disk read operations
             2. [`90 days of data`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_reads:rate1m/90%20days%20of%20data) - This contains 3 months of metric data collected for the Dgraph disk write operations
             3. Other `.json` files which contain much smaller sample sizes of metric data
          2. [`badger_disk_writes:rate1m`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_writes:rate1m) which will contain mainly:
             1. [`1month of data (Aug 13-Sep 13)`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_reads:rate1m/1month%20of%20data%20(Aug%2013-Sep%2013)) - This contains 1 month of metric data collected for Dgraph disk read operations
             2. [`90 days of data`](./metrics/prometheus-route-aiops-prod-prometheus-predict.cloud.paas.psi.redhat.com/badger_disk_reads:rate1m/90%20days%20of%20data) - This contains 3 months of metric data collected for the Dgraph disk write operations
             3. Other `.json` files which contain much smaller sample sizes of metric data
  2. an [`Introduction_TimeSeries_Anomaly_Detection.ipynb`](./anomaly-detection/Introduction_TimeSeries_Anomaly_Detection.ipynb) notebook, where we will learn how to build a machine learning model to perform time series forecasting and predict anomalies
* a [`prometheus-api-client`](./prometheus-api-client) folder, which contains:      
  1. an [`Introduction_Prometheus_API_Client.ipynb`](./Introduction_Prometheus_API_Client.ipynb) notebook, where we will explore how to use the Prometheus API Client library for fetching and manipulating metric data from a Prometheus host
