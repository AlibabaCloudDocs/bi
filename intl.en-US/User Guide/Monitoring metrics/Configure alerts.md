# Configure alerts {#concept_183315 .concept}

After configuring the collection of metrics, you need to configure alerts on the Metrics page.

1.  Select a metric, click the **More** icon and select **Alerts** from the More drop-down list.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/157093/156410589644315_en-US.png)

2.  In the **Configure Alert** dialog box, configure **Alert Rule**, **Alert Method**, **Alert Recipient**, ane **Enable Alert**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/157093/156410589644316_en-US.png)

    Alert rule

    -   **Whenever the metric value is greater than**: sets an upper limit. When the actual value of a metric exceeds the upper limit, an alert appears.
    -   **Whenever the metric value is less than**: sets a lower limit. When the actual value of a metric is below the lower limit, an alert appears.
    -   **Period-on-Period Change \(%\)**: sets a range. When the pop change rate is out of range, an alert appears.
    **Note:** Currently, the only alert method supported is email. Alert methods such as DingTalk, SMS, and phone are in development. Alerts can only be sent to organization members by email. Make sure that recipients have set their email in the Personal dialog box to receive alerts.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/83625/156410589639107_en-US.png)

    The verification code sent to recipients will expire in two days. Alerts are sent according to different anomalies.

    -   Emails are sent when metric anomalies occur.
    -   Emails are sent to recipients once a day when anomalies of metrics with daily and monthly granularity occur.
    -   A maximum of five emails a day are sent when anomalies of metrics with hourly granularity occur.
3.  Click **OK**.

