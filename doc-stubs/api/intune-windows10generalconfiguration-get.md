---
title: "Get windows10GeneralConfiguration"
description: "Read the properties and relationships of a windows10GeneralConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get windows10GeneralConfiguration
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of a [windows10GeneralConfiguration](../resources/intune-windows10generalconfiguration.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET ** Entity URI for microsoft.graph.windows10GeneralConfiguration not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [windows10GeneralConfiguration](../resources/intune-windows10generalconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_windows10generalconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Entity URI for microsoft.graph.windows10GeneralConfiguration not found
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.windows10GeneralConfiguration"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.windows10GeneralConfiguration",
    "id": "606f88d3-88d3-606f-d388-6f60d3886f60",
    "lastModifiedDateTime": "String (timestamp)",
    "roleScopeTagIds": [
      "String"
    ],
    "supportsScopeTags": "Boolean",
    "deviceManagementApplicabilityRuleOsEdition": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
    },
    "deviceManagementApplicabilityRuleOsVersion": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
    },
    "deviceManagementApplicabilityRuleDeviceMode": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
    },
    "createdDateTime": "String (timestamp)",
    "description": "String",
    "displayName": "String",
    "version": "Integer",
    "taskManagerBlockEndTask": "Boolean",
    "energySaverOnBatteryThresholdPercentage": "Integer",
    "energySaverPluggedInThresholdPercentage": "Integer",
    "powerLidCloseActionOnBattery": "String",
    "powerLidCloseActionPluggedIn": "String",
    "powerButtonActionOnBattery": "String",
    "powerButtonActionPluggedIn": "String",
    "powerSleepButtonActionOnBattery": "String",
    "powerSleepButtonActionPluggedIn": "String",
    "powerHybridSleepOnBattery": "String",
    "powerHybridSleepPluggedIn": "String",
    "windows10AppsForceUpdateSchedule": {
      "@odata.type": "microsoft.graph.windows10AppsForceUpdateSchedule"
    },
    "enableAutomaticRedeployment": "Boolean",
    "microsoftAccountSignInAssistantSettings": "String",
    "authenticationAllowSecondaryDevice": "Boolean",
    "authenticationWebSignIn": "String",
    "authenticationPreferredAzureADTenantDomainName": "String",
    "cryptographyAllowFipsAlgorithmPolicy": "Boolean",
    "displayAppListWithGdiDPIScalingTurnedOn": [
      "String"
    ],
    "displayAppListWithGdiDPIScalingTurnedOff": [
      "String"
    ],
    "enterpriseCloudPrintDiscoveryEndPoint": "String",
    "enterpriseCloudPrintOAuthAuthority": "String",
    "enterpriseCloudPrintOAuthClientIdentifier": "String",
    "enterpriseCloudPrintResourceIdentifier": "String",
    "enterpriseCloudPrintDiscoveryMaxLimit": "Integer",
    "enterpriseCloudPrintMopriaDiscoveryResourceIdentifier": "String",
    "experienceDoNotSyncBrowserSettings": "String",
    "messagingBlockSync": "Boolean",
    "messagingBlockMMS": "Boolean",
    "messagingBlockRichCommunicationServices": "Boolean",
    "printerNames": [
      "String"
    ],
    "printerDefaultName": "String",
    "printerBlockAddition": "Boolean",
    "searchBlockDiacritics": "Boolean",
    "searchDisableAutoLanguageDetection": "Boolean",
    "searchDisableIndexingEncryptedItems": "Boolean",
    "searchEnableRemoteQueries": "Boolean",
    "searchDisableUseLocation": "Boolean",
    "searchDisableLocation": "Boolean",
    "searchDisableIndexerBackoff": "Boolean",
    "searchDisableIndexingRemovableDrive": "Boolean",
    "searchEnableAutomaticIndexSizeManangement": "Boolean",
    "searchBlockWebResults": "Boolean",
    "findMyFiles": "String",
    "securityBlockAzureADJoinedDevicesAutoEncryption": "Boolean",
    "diagnosticsDataSubmissionMode": "String",
    "oneDriveDisableFileSync": "Boolean",
    "systemTelemetryProxyServer": "String",
    "edgeTelemetryForMicrosoft365Analytics": "String",
    "inkWorkspaceAccess": "String",
    "inkWorkspaceAccessState": "String",
    "inkWorkspaceBlockSuggestedApps": "Boolean",
    "smartScreenEnableAppInstallControl": "Boolean",
    "smartScreenAppInstallControl": "String",
    "personalizationDesktopImageUrl": "String",
    "personalizationLockScreenImageUrl": "String",
    "bluetoothAllowedServices": [
      "String"
    ],
    "bluetoothBlockAdvertising": "Boolean",
    "bluetoothBlockPromptedProximalConnections": "Boolean",
    "bluetoothBlockDiscoverableMode": "Boolean",
    "bluetoothBlockPrePairing": "Boolean",
    "edgeBlockAutofill": "Boolean",
    "edgeBlocked": "Boolean",
    "edgeCookiePolicy": "String",
    "edgeBlockDeveloperTools": "Boolean",
    "edgeBlockSendingDoNotTrackHeader": "Boolean",
    "edgeBlockExtensions": "Boolean",
    "edgeBlockInPrivateBrowsing": "Boolean",
    "edgeBlockJavaScript": "Boolean",
    "edgeBlockPasswordManager": "Boolean",
    "edgeBlockAddressBarDropdown": "Boolean",
    "edgeBlockCompatibilityList": "Boolean",
    "edgeClearBrowsingDataOnExit": "Boolean",
    "edgeAllowStartPagesModification": "Boolean",
    "edgeDisableFirstRunPage": "Boolean",
    "edgeBlockLiveTileDataCollection": "Boolean",
    "edgeSyncFavoritesWithInternetExplorer": "Boolean",
    "edgeFavoritesListLocation": "String",
    "edgeBlockEditFavorites": "Boolean",
    "edgeNewTabPageURL": "String",
    "edgeHomeButtonConfiguration": {
      "@odata.type": "microsoft.graph.edgeHomeButtonConfiguration"
    },
    "edgeHomeButtonConfigurationEnabled": "Boolean",
    "edgeOpensWith": "String",
    "edgeBlockSideloadingExtensions": "Boolean",
    "edgeRequiredExtensionPackageFamilyNames": [
      "String"
    ],
    "edgeBlockPrinting": "Boolean",
    "edgeFavoritesBarVisibility": "String",
    "edgeBlockSavingHistory": "Boolean",
    "edgeBlockFullScreenMode": "Boolean",
    "edgeBlockWebContentOnNewTabPage": "Boolean",
    "edgeBlockTabPreloading": "Boolean",
    "edgeBlockPrelaunch": "Boolean",
    "edgeShowMessageWhenOpeningInternetExplorerSites": "String",
    "edgePreventCertificateErrorOverride": "Boolean",
    "edgeKioskModeRestriction": "String",
    "edgeKioskResetAfterIdleTimeInMinutes": "Integer",
    "cellularBlockDataWhenRoaming": "Boolean",
    "cellularBlockVpn": "Boolean",
    "cellularBlockVpnWhenRoaming": "Boolean",
    "cellularData": "String",
    "defenderRequireRealTimeMonitoring": "Boolean",
    "defenderRequireBehaviorMonitoring": "Boolean",
    "defenderRequireNetworkInspectionSystem": "Boolean",
    "defenderScanDownloads": "Boolean",
    "defenderScheduleScanEnableLowCpuPriority": "Boolean",
    "defenderDisableCatchupQuickScan": "Boolean",
    "defenderDisableCatchupFullScan": "Boolean",
    "defenderScanScriptsLoadedInInternetExplorer": "Boolean",
    "defenderBlockEndUserAccess": "Boolean",
    "defenderSignatureUpdateIntervalInHours": "Integer",
    "defenderMonitorFileActivity": "String",
    "defenderDaysBeforeDeletingQuarantinedMalware": "Integer",
    "defenderScanMaxCpu": "Integer",
    "defenderScanArchiveFiles": "Boolean",
    "defenderScanIncomingMail": "Boolean",
    "defenderScanRemovableDrivesDuringFullScan": "Boolean",
    "defenderScanMappedNetworkDrivesDuringFullScan": "Boolean",
    "defenderScanNetworkFiles": "Boolean",
    "defenderRequireCloudProtection": "Boolean",
    "defenderCloudBlockLevel": "String",
    "defenderCloudExtendedTimeout": "Integer",
    "defenderCloudExtendedTimeoutInSeconds": "Integer",
    "defenderPromptForSampleSubmission": "String",
    "defenderScheduledQuickScanTime": "String (time of day)",
    "defenderScanType": "String",
    "defenderSystemScanSchedule": "String",
    "defenderScheduledScanTime": "String (time of day)",
    "defenderPotentiallyUnwantedAppAction": "String",
    "defenderPotentiallyUnwantedAppActionSetting": "String",
    "defenderSubmitSamplesConsentType": "String",
    "defenderBlockOnAccessProtection": "Boolean",
    "defenderDetectedMalwareActions": {
      "@odata.type": "microsoft.graph.defenderDetectedMalwareActions"
    },
    "defenderFileExtensionsToExclude": [
      "String"
    ],
    "defenderFilesAndFoldersToExclude": [
      "String"
    ],
    "defenderProcessesToExclude": [
      "String"
    ],
    "lockScreenAllowTimeoutConfiguration": "Boolean",
    "lockScreenBlockActionCenterNotifications": "Boolean",
    "lockScreenBlockCortana": "Boolean",
    "lockScreenBlockToastNotifications": "Boolean",
    "lockScreenTimeoutInSeconds": "Integer",
    "lockScreenActivateAppsWithVoice": "String",
    "passwordBlockSimple": "Boolean",
    "passwordExpirationDays": "Integer",
    "passwordMinimumLength": "Integer",
    "passwordMinutesOfInactivityBeforeScreenTimeout": "Integer",
    "passwordMinimumCharacterSetCount": "Integer",
    "passwordPreviousPasswordBlockCount": "Integer",
    "passwordRequired": "Boolean",
    "passwordRequireWhenResumeFromIdleState": "Boolean",
    "passwordRequiredType": "String",
    "passwordSignInFailureCountBeforeFactoryReset": "Integer",
    "passwordMinimumAgeInDays": "Integer",
    "privacyAdvertisingId": "String",
    "privacyAutoAcceptPairingAndConsentPrompts": "Boolean",
    "privacyDisableLaunchExperience": "Boolean",
    "privacyBlockInputPersonalization": "Boolean",
    "privacyBlockPublishUserActivities": "Boolean",
    "privacyBlockActivityFeed": "Boolean",
    "activateAppsWithVoice": "String",
    "startBlockUnpinningAppsFromTaskbar": "Boolean",
    "startMenuAppListVisibility": "String",
    "startMenuHideChangeAccountSettings": "Boolean",
    "startMenuHideFrequentlyUsedApps": "Boolean",
    "startMenuHideHibernate": "Boolean",
    "startMenuHideLock": "Boolean",
    "startMenuHidePowerButton": "Boolean",
    "startMenuHideRecentJumpLists": "Boolean",
    "startMenuHideRecentlyAddedApps": "Boolean",
    "startMenuHideRestartOptions": "Boolean",
    "startMenuHideShutDown": "Boolean",
    "startMenuHideSignOut": "Boolean",
    "startMenuHideSleep": "Boolean",
    "startMenuHideSwitchAccount": "Boolean",
    "startMenuHideUserTile": "Boolean",
    "startMenuLayoutEdgeAssetsXml": "Binary",
    "startMenuLayoutXml": "Binary",
    "startMenuMode": "String",
    "startMenuPinnedFolderDocuments": "String",
    "startMenuPinnedFolderDownloads": "String",
    "startMenuPinnedFolderFileExplorer": "String",
    "startMenuPinnedFolderHomeGroup": "String",
    "startMenuPinnedFolderMusic": "String",
    "startMenuPinnedFolderNetwork": "String",
    "startMenuPinnedFolderPersonalFolder": "String",
    "startMenuPinnedFolderPictures": "String",
    "startMenuPinnedFolderSettings": "String",
    "startMenuPinnedFolderVideos": "String",
    "settingsBlockSettingsApp": "Boolean",
    "settingsBlockSystemPage": "Boolean",
    "settingsBlockDevicesPage": "Boolean",
    "settingsBlockNetworkInternetPage": "Boolean",
    "settingsBlockPersonalizationPage": "Boolean",
    "settingsBlockAccountsPage": "Boolean",
    "settingsBlockTimeLanguagePage": "Boolean",
    "settingsBlockEaseOfAccessPage": "Boolean",
    "settingsBlockPrivacyPage": "Boolean",
    "settingsBlockUpdateSecurityPage": "Boolean",
    "settingsBlockAppsPage": "Boolean",
    "settingsBlockGamingPage": "Boolean",
    "windowsSpotlightBlockConsumerSpecificFeatures": "Boolean",
    "windowsSpotlightBlocked": "Boolean",
    "windowsSpotlightBlockOnActionCenter": "Boolean",
    "windowsSpotlightBlockTailoredExperiences": "Boolean",
    "windowsSpotlightBlockThirdPartyNotifications": "Boolean",
    "windowsSpotlightBlockWelcomeExperience": "Boolean",
    "windowsSpotlightBlockWindowsTips": "Boolean",
    "windowsSpotlightConfigureOnLockScreen": "String",
    "networkProxyApplySettingsDeviceWide": "Boolean",
    "networkProxyDisableAutoDetect": "Boolean",
    "networkProxyAutomaticConfigurationUrl": "String",
    "networkProxyServer": {
      "@odata.type": "microsoft.graph.windows10NetworkProxyServer"
    },
    "accountsBlockAddingNonMicrosoftAccountEmail": "Boolean",
    "antiTheftModeBlocked": "Boolean",
    "bluetoothBlocked": "Boolean",
    "cameraBlocked": "Boolean",
    "connectedDevicesServiceBlocked": "Boolean",
    "certificatesBlockManualRootCertificateInstallation": "Boolean",
    "copyPasteBlocked": "Boolean",
    "cortanaBlocked": "Boolean",
    "deviceManagementBlockFactoryResetOnMobile": "Boolean",
    "deviceManagementBlockManualUnenroll": "Boolean",
    "safeSearchFilter": "String",
    "edgeBlockPopups": "Boolean",
    "edgeBlockSearchSuggestions": "Boolean",
    "edgeBlockSearchEngineCustomization": "Boolean",
    "edgeBlockSendingIntranetTrafficToInternetExplorer": "Boolean",
    "edgeSendIntranetTrafficToInternetExplorer": "Boolean",
    "edgeRequireSmartScreen": "Boolean",
    "edgeEnterpriseModeSiteListLocation": "String",
    "edgeFirstRunUrl": "String",
    "edgeSearchEngine": {
      "@odata.type": "microsoft.graph.edgeSearchEngineBase"
    },
    "edgeHomepageUrls": [
      "String"
    ],
    "edgeBlockAccessToAboutFlags": "Boolean",
    "smartScreenBlockPromptOverride": "Boolean",
    "smartScreenBlockPromptOverrideForFiles": "Boolean",
    "webRtcBlockLocalhostIpAddress": "Boolean",
    "internetSharingBlocked": "Boolean",
    "settingsBlockAddProvisioningPackage": "Boolean",
    "settingsBlockRemoveProvisioningPackage": "Boolean",
    "settingsBlockChangeSystemTime": "Boolean",
    "settingsBlockEditDeviceName": "Boolean",
    "settingsBlockChangeRegion": "Boolean",
    "settingsBlockChangeLanguage": "Boolean",
    "settingsBlockChangePowerSleep": "Boolean",
    "locationServicesBlocked": "Boolean",
    "microsoftAccountBlocked": "Boolean",
    "microsoftAccountBlockSettingsSync": "Boolean",
    "nfcBlocked": "Boolean",
    "resetProtectionModeBlocked": "Boolean",
    "screenCaptureBlocked": "Boolean",
    "storageBlockRemovableStorage": "Boolean",
    "storageRequireMobileDeviceEncryption": "Boolean",
    "usbBlocked": "Boolean",
    "voiceRecordingBlocked": "Boolean",
    "wiFiBlockAutomaticConnectHotspots": "Boolean",
    "wiFiBlocked": "Boolean",
    "wiFiBlockManualConfiguration": "Boolean",
    "wiFiScanInterval": "Integer",
    "wirelessDisplayBlockProjectionToThisDevice": "Boolean",
    "wirelessDisplayBlockUserInputFromReceiver": "Boolean",
    "wirelessDisplayRequirePinForPairing": "Boolean",
    "windowsStoreBlocked": "Boolean",
    "appsAllowTrustedAppsSideloading": "String",
    "windowsStoreBlockAutoUpdate": "Boolean",
    "developerUnlockSetting": "String",
    "sharedUserAppDataAllowed": "Boolean",
    "appsBlockWindowsStoreOriginatedApps": "Boolean",
    "windowsStoreEnablePrivateStoreOnly": "Boolean",
    "storageRestrictAppDataToSystemVolume": "Boolean",
    "storageRestrictAppInstallToSystemVolume": "Boolean",
    "gameDvrBlocked": "Boolean",
    "experienceBlockDeviceDiscovery": "Boolean",
    "experienceBlockErrorDialogWhenNoSIM": "Boolean",
    "experienceBlockTaskSwitcher": "Boolean",
    "logonBlockFastUserSwitching": "Boolean",
    "tenantLockdownRequireNetworkDuringOutOfBoxExperience": "Boolean",
    "appManagementMSIAllowUserControlOverInstall": "Boolean",
    "appManagementMSIAlwaysInstallWithElevatedPrivileges": "Boolean",
    "dataProtectionBlockDirectMemoryAccess": "Boolean",
    "appManagementPackageFamilyNamesToLaunchAfterLogOn": [
      "String"
    ],
    "uninstallBuiltInApps": "Boolean",
    "configureTimeZone": "String"
  }
}
```

