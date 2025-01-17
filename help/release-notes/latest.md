---
title: Latest Analytics release notes
description: View the current Adobe Analytics release notes.
feature: Release Notes
exl-id: 97d16d5c-a8b3-48f3-8acb-96033cc691dc
---
# Current Adobe Analytics release notes (June 2022)

>[!NOTE]
>
>This page contains pre-release information and is subject to change.

**Last update**: June 10, 2022

## Related resources

* [Previous release notes for 2022](/help/release-notes/2022.md)
* [Customer Journey Analytics release notes](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html)
* [Media Analytics release notes](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html)
* The latest release updates for [Adobe Experience Cloud products](https://business.adobe.com/products/adobe-experience-cloud-products.html)

## New features in Adobe Analytics

| Feature | Description | [Targeted Date](releases.md)  |
| ----------- | ---------- | ------- |
| New Flow visualization UI | Provides additional functionality to our Flow visualization to make it more powerful and capable. [Learn more](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/visualizations/flow/create-flow.html?lang=en) | June 15, 2022 |
| Share annotations in Mobile scorecards | You can display annotations that are created in Workspace—in Mobile Scorecards. This allows you to share contextual data nuances and insights about your organization and campaigns directly within Mobile Scorecard projects, viewable in the Analytics dashboards mobile app. Learn more (to follow) | June 15, 2022 |
| Support for product syntax version of Merchandising Variables with Edge Collection | You can now set merchandising variables using the equivalent of the product syntax by setting the relevant XDM fields. Find more detail about product syntax for merchandising variables [here](https://experienceleague.adobe.com/docs/analytics/admin/admin-tools/conversion-variables/merchandising-evars.html?lang=en). See the mappings for product syntax [here](https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/variable-mapping.html?lang=en#aep-edge). | June 15, 2022|
| Populate Lifecycle dimensions and metrics through Experience Edge | Mobile Lifecycle data sent via Experience Edge will now appear in Analytics reporting. See documentation for details on which XDM fields map to existing mobile Lifecycle reporting. [Learn more](https://experienceleague.adobe.com/docs/analytics/implementation/aep-edge/variable-mapping.html) | May 27, 2022 |
| New classifications experience - Phase 1 | This phased release of a new classification set user experience significantly improves visibility into customer-owned classification data. GA is estimated at early 2023. | Limited testing starts June 15, 2022 |

{style="table-layout:auto"}

### Fixes in Adobe Analytics

AN-251686; AN-283542; AN-286572; AN-286945; AN-286784; AN-286944; AN-287012; AN-287319; AN-287333; AN-287348; AN-287429; AN-288238; AN-288281; AN-288660; AN-288769; AN-288798; AN-288871; AN-288872; AN-288941; AN-288951; AN-288952; AN-288956; AN-289062; AN-289340; AN-289346; AN-289488; AN-289562; AN-289580; AN-289861; AN-289892; 

### Important notices for Adobe Analytics administrators

| Notice | Date Added or Updated  | Description |
| ----------- | ---------- | ---------- |
| **Pausing scheduled reports in Reports & Analytics** | June 8, 2022 | On April 21, 2022, we announced the deprecation of several features specific to scheduled reports in preparation for the previously announced end of life for Reports & Analytics. These features included the ability to schedule new reports as well as new data extracts.<p>In response to customer requests seeking an extension and to ease the transition from Reports and Analytics, we have decided to extend access to these features until **Jan 31, 2023**. Please note that expiration windows for both reports and data extracts will continue to be limited to nine months; report and data extract delivery will pause at the end of this period unless the schedule is reactivated.<p>To reiterate, these features will be deprecated on January 31, 2023. Before this date, you must migrate your scheduled reporting to one of the other mechanisms available to you in Adobe Analytics. For additional questions or support, please reach out to Adobe Customer Care. [Learn more](/help/analyze/reports-analytics/scheduled-reports-eol.md) |
| **Pausing scheduled tasks in Report Builder** | June 8, 2022 | On April 21, 2022, we rolled out changes to scheduled tasks in Report Builder as part of our performance and delivery optimization efforts. These changes included removing the ability to have scheduled deliveries “end after x occurrences.” In response to several customer requests seeking more time to explore and implement alternatives, we have decided to restore this option in a limited fashion until **Jan 31, 2023**.<p>You can continue to schedule hourly Report Builder tasks and have them end after a maximum of 99 occurrences. Please note that the rollback only applies to hourly tasks; the “end after x occurrences” will remain unavailable for all other delivery intervals (daily, weekly, monthly, and yearly). Please note that this option will be deprecated on January 31, 2023. For more questions or support, please reach out to Adobe Customer Care. [Learn more](/help/analyze/report-builder/r-arb-scheduled-reports.md)|
| **SFTP upgrade** | May 9, 2022 | Previously, we had communicated that Adobe would upgrade its Secure File Transfer Protocol (SFTP) services in May 2022 to provide improved security for file transfer. We have postponed this upgrade to the **summer of 2022**. When this change takes place, certain SFTP client configurations will no longer be supported. This impacts only data sent to or retrieved from Adobe Analytics using SFTP. The FTP protocol is not impacted. In order to avoid service disruptions, please ensure that your SFTP clients (code, tools, services) are in accordance with the changes detailed [here](https://experienceleague.adobe.com/docs/analytics/export/ftp-and-sftp/secure-file-transfer-protocol/sftp-upgrade.html). |
| **Update to browser encryption methods supported for certain customers** | March 28, 2022 | Adobe offers two cipher security levels to meet varying customer needs for security on first-party data collection. On **June 23, 2022** support is removed for certain HTTPS encryption algorithms, known as ciphers, for customers with their security level set to “High”. This action means that some older operating systems are no longer be able to send data to Analytics because they do not support modern encryption methods. Customers using the default “Standard” cipher security settings are not impacted. All customers currently using the “High” setting have already been contacted directly. A detailed list of the ciphers affected by this |
| **2022 ISO region updates** | March 11, 2021 | Adobe performed 2022 ISO region updates on **June 10, 2022**. Expect to see minor geo information updates following this release. |
| **EOL for [!DNL Reports & Analytics]** | January 4, 2022 | Effective **December 31, 2023**, Adobe intends to discontinue [!DNL Reports & Analytics] and its accompanying reports and features. The reports, visualizations, and underlying technology that power [!DNL Reports & Analytics] no longer meet Adobe’s technology standards. Most [!DNL Reports & Analytics] features are available in [Analysis Workspace](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/home.html). Since the release of Analysis Workspace in 2015, [!DNL Reports & Analytics] functionality and capabilities have been moved to Analysis Workspace and a threshold of workflow parity has been reached. [This notice](https://spark.adobe.com/page/6WnF8JK6IRDhf/) explains the end-of-life process. |

{style="table-layout:auto"}

### AppMeasurement

For the latest updates on AppMeasurement releases (Version 2.22.4), please refer to [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en).

