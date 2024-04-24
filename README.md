# posit_connect_metrics_example

Reference: <https://solutions.posit.co/operations/connect-apis/> 

Disclaimer from Katie: 
> In the past, content visits for Plumber, Voila, Streamlit, Dash, and Bokeh were over-counted.  The counting was corrected in Connect v 2023.10 for metrics collected going forward.
> When querying the Connect server API endpoint /v1/instrumentation/content/visits , the version of the data counting method is reported in the field min_data_version. This is, by default, set to 3 which returns the correct counts.  They may have some older data recorded with a min_data_version less than 3, but it may not be accurate.
> References:

- <https://docs.posit.co/connect/api/#get-/v1/instrumentation/content/visits:~:text=html%20qu[…]s%20how%20to%20interpret%20data_version%20values.,-from>
- <https://docs.posit.co/connect/admin/operational-metrics/#content-visit-events>
