# Device configuration in Microsoft Intune

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.

Use the Microsoft Intune Device Configuration workload to manage settings and features on all of the devices you manage.

The following Graph resources are available to manage settings and features on devices in Intune:

- [AirPrint destination](intune_deviceconfig_airprintdestination.md)
- [Android certificate profile base](intune_deviceconfig_androidcertificateprofilebase.md)
- [Android compliance policy](intune_deviceconfig_androidcompliancepolicy.md)
- [Android custom configuration](intune_deviceconfig_androidcustomconfiguration.md)
- [Android device owner battery plugged mode](intune_deviceconfig_androiddeviceownerbatterypluggedmode.md)
- [Android device owner default app permission policy type](intune_deviceconfig_androiddeviceownerdefaultapppermissionpolicytype.md)
- [Android device owner general device configuration](intune_deviceconfig_androiddeviceownergeneraldeviceconfiguration.md)
- [Android device owner required password type](intune_deviceconfig_androiddeviceownerrequiredpasswordtype.md)
- [Android eap type](intune_deviceconfig_androideaptype.md)
- [Android EAS email profile configuration](intune_deviceconfig_androideasemailprofileconfiguration.md)
- [Android enterprise Wi-Fi configuration](intune_deviceconfig_androidenterprisewificonfiguration.md)
- [Android for Work certificate profile base](intune_deviceconfig_androidforworkcertificateprofilebase.md)
- [Android for Work compliance policy](intune_deviceconfig_androidforworkcompliancepolicy.md)
- [Android for Work cross profile data sharing type](intune_deviceconfig_androidforworkcrossprofiledatasharingtype.md)
- [Android for Work custom configuration](intune_deviceconfig_androidforworkcustomconfiguration.md)
- [Android for Work default app permission policy type](intune_deviceconfig_androidforworkdefaultapppermissionpolicytype.md)
- [Android for Work EAS email profile base](intune_deviceconfig_androidforworkeasemailprofilebase.md)
- [Android for Work enterprise Wi-Fi configuration](intune_deviceconfig_androidforworkenterprisewificonfiguration.md)
- [Android for Work general device configuration](intune_deviceconfig_androidforworkgeneraldeviceconfiguration.md)
- [Android for Work Gmail EAS configuration](intune_deviceconfig_androidforworkgmaileasconfiguration.md)
- [Android for Work imported PFX certificate profile](intune_deviceconfig_androidforworkimportedpfxcertificateprofile.md)
- [Android for Work nine work EAS configuration](intune_deviceconfig_androidforworknineworkeasconfiguration.md)
- [Android for Work PKCS certificate profile](intune_deviceconfig_androidforworkpkcscertificateprofile.md)
- [Android for Work required password type](intune_deviceconfig_androidforworkrequiredpasswordtype.md)
- [Android for Work SCEP certificate profile](intune_deviceconfig_androidforworkscepcertificateprofile.md)
- [Android for Work trusted root certificate](intune_deviceconfig_androidforworktrustedrootcertificate.md)
- [Android for Work VPN configuration](intune_deviceconfig_androidforworkvpnconfiguration.md)
- [Android for Work VPN connection type](intune_deviceconfig_androidforworkvpnconnectiontype.md)
- [Android for Work Wi-Fi configuration](intune_deviceconfig_androidforworkwificonfiguration.md)
- [Android general device configuration](intune_deviceconfig_androidgeneraldeviceconfiguration.md)
- [Android imported PFX certificate profile](intune_deviceconfig_androidimportedpfxcertificateprofile.md)
- [Android PKCS certificate profile](intune_deviceconfig_androidpkcscertificateprofile.md)
- [Android required password type](intune_deviceconfig_androidrequiredpasswordtype.md)
- [Android SCEP certificate profile](intune_deviceconfig_androidscepcertificateprofile.md)
- [Android trusted root certificate](intune_deviceconfig_androidtrustedrootcertificate.md)
- [Android username source](intune_deviceconfig_androidusernamesource.md)
- [Android VPN configuration](intune_deviceconfig_androidvpnconfiguration.md)
- [Android VPN connection type](intune_deviceconfig_androidvpnconnectiontype.md)
- [Android Wi-Fi configuration](intune_deviceconfig_androidwificonfiguration.md)
- [Android Wi-Fi security type](intune_deviceconfig_androidwifisecuritytype.md)
- [Android work profile certificate profile base](intune_deviceconfig_androidworkprofilecertificateprofilebase.md)
- [Android work profile compliance policy](intune_deviceconfig_androidworkprofilecompliancepolicy.md)
- [Android work profile cross profile data sharing type](intune_deviceconfig_androidworkprofilecrossprofiledatasharingtype.md)
- [Android work profile custom configuration](intune_deviceconfig_androidworkprofilecustomconfiguration.md)
- [Android work profile default app permission policy type](intune_deviceconfig_androidworkprofiledefaultapppermissionpolicytype.md)
- [Android work profile EAS email profile base](intune_deviceconfig_androidworkprofileeasemailprofilebase.md)
- [Android work profile enterprise Wi-Fi configuration](intune_deviceconfig_androidworkprofileenterprisewificonfiguration.md)
- [Android work profile general device configuration](intune_deviceconfig_androidworkprofilegeneraldeviceconfiguration.md)
- [Android work profile Gmail EAS configuration](intune_deviceconfig_androidworkprofilegmaileasconfiguration.md)
- [Android work profile nine work EAS configuration](intune_deviceconfig_androidworkprofilenineworkeasconfiguration.md)
- [Android work profile PKCS certificate profile](intune_deviceconfig_androidworkprofilepkcscertificateprofile.md)
- [Android work profile required password type](intune_deviceconfig_androidworkprofilerequiredpasswordtype.md)
- [Android work profile SCEP certificate profile](intune_deviceconfig_androidworkprofilescepcertificateprofile.md)
- [Android work profile trusted root certificate](intune_deviceconfig_androidworkprofiletrustedrootcertificate.md)
- [Android work profile VPN configuration](intune_deviceconfig_androidworkprofilevpnconfiguration.md)
- [Android work profile VPN connection type](intune_deviceconfig_androidworkprofilevpnconnectiontype.md)
- [Android work profile Wi-Fi configuration](intune_deviceconfig_androidworkprofilewificonfiguration.md)
- [App list item](intune_deviceconfig_applistitem.md)
- [App list type](intune_deviceconfig_applisttype.md)
- [App locker application control type](intune_deviceconfig_applockerapplicationcontroltype.md)
- [Apple device features configuration base](intune_deviceconfig_appledevicefeaturesconfigurationbase.md)
- [Apple subject name format](intune_deviceconfig_applesubjectnameformat.md)
- [Apple VPN configuration](intune_deviceconfig_applevpnconfiguration.md)
- [Apple VPN connection type](intune_deviceconfig_applevpnconnectiontype.md)
- [Application guard block clipboard sharing type](intune_deviceconfig_applicationguardblockclipboardsharingtype.md)
- [Application guard block file transfer type](intune_deviceconfig_applicationguardblockfiletransfertype.md)
- [Automatic update mode](intune_deviceconfig_automaticupdatemode.md)
- [BitLocker encryption method](intune_deviceconfig_bitlockerencryptionmethod.md)
- [BitLocker fixed drive policy](intune_deviceconfig_bitlockerfixeddrivepolicy.md)
- [BitLocker recovery information type](intune_deviceconfig_bitlockerrecoveryinformationtype.md)
- [BitLocker recovery options](intune_deviceconfig_bitlockerrecoveryoptions.md)
- [BitLocker removable drive policy](intune_deviceconfig_bitlockerremovabledrivepolicy.md)
- [BitLocker system drive policy](intune_deviceconfig_bitlockersystemdrivepolicy.md)
- [Cart to class association](intune_deviceconfig_carttoclassassociation.md)
- [Certificate destination store](intune_deviceconfig_certificatedestinationstore.md)
- [Certificate store](intune_deviceconfig_certificatestore.md)
- [Certificate validity period scale](intune_deviceconfig_certificatevalidityperiodscale.md)
- [Configuration usage](intune_deviceconfig_configurationusage.md)
- [Day of week](intune_deviceconfig_dayofweek.md)
- [Default device compliance policy](intune_deviceconfig_defaultdevicecompliancepolicy.md)
- [Defender attack surface type](intune_deviceconfig_defenderattacksurfacetype.md)
- [Defender cloud block level type](intune_deviceconfig_defendercloudblockleveltype.md)
- [Defender detected malware actions](intune_deviceconfig_defenderdetectedmalwareactions.md)
- [Defender monitor file activity](intune_deviceconfig_defendermonitorfileactivity.md)
- [Defender potentially unwanted app action](intune_deviceconfig_defenderpotentiallyunwantedappaction.md)
- [Defender prompt for sample submission](intune_deviceconfig_defenderpromptforsamplesubmission.md)
- [Defender protection type](intune_deviceconfig_defenderprotectiontype.md)
- [Defender scan type](intune_deviceconfig_defenderscantype.md)
- [Defender schedule scan day](intune_deviceconfig_defenderschedulescanday.md)
- [Defender security center IT contact display type](intune_deviceconfig_defendersecuritycenteritcontactdisplaytype.md)
- [Defender security center notifications from app type](intune_deviceconfig_defendersecuritycenternotificationsfromapptype.md)
- [Defender submit samples consent type](intune_deviceconfig_defendersubmitsamplesconsenttype.md)
- [Defender threat action](intune_deviceconfig_defenderthreataction.md)
- [Device compliance action item](intune_deviceconfig_devicecomplianceactionitem.md)
- [Device compliance action type](intune_deviceconfig_devicecomplianceactiontype.md)
- [Device compliance device overview](intune_deviceconfig_devicecompliancedeviceoverview.md)
- [Device compliance device status](intune_deviceconfig_devicecompliancedevicestatus.md)
- [Device compliance policy](intune_deviceconfig_devicecompliancepolicy.md)
- [Device compliance policy assignment](intune_deviceconfig_devicecompliancepolicyassignment.md)
- [Device compliance policy device state summary](intune_deviceconfig_devicecompliancepolicydevicestatesummary.md)
- [Device compliance policy setting state](intune_deviceconfig_devicecompliancepolicysettingstate.md)
- [Device compliance policy setting state summary](intune_deviceconfig_devicecompliancepolicysettingstatesummary.md)
- [Device compliance scheduled action for rule](intune_deviceconfig_devicecompliancescheduledactionforrule.md)
- [Device compliance setting state](intune_deviceconfig_devicecompliancesettingstate.md)
- [Device compliance user overview](intune_deviceconfig_devicecomplianceuseroverview.md)
- [Device compliance user status](intune_deviceconfig_devicecomplianceuserstatus.md)
- [Device configuration](intune_deviceconfig_deviceconfiguration.md)
- [Device configuration assignment](intune_deviceconfig_deviceconfigurationassignment.md)
- [Device configuration device overview](intune_deviceconfig_deviceconfigurationdeviceoverview.md)
- [Device configuration device state summary](intune_deviceconfig_deviceconfigurationdevicestatesummary.md)
- [Device configuration device status](intune_deviceconfig_deviceconfigurationdevicestatus.md)
- [Device configuration group assignment](intune_deviceconfig_deviceconfigurationgroupassignment.md)
- [Device configuration setting state](intune_deviceconfig_deviceconfigurationsettingstate.md)
- [Device configuration user overview](intune_deviceconfig_deviceconfigurationuseroverview.md)
- [Device configuration user state summary](intune_deviceconfig_deviceconfigurationuserstatesummary.md)
- [Device configuration user status](intune_deviceconfig_deviceconfigurationuserstatus.md)
- [Device guard local system authority credential guard type](intune_deviceconfig_deviceguardlocalsystemauthoritycredentialguardtype.md)
- [Device management settings](intune_deviceconfig_devicemanagementsettings.md)
- [Device platform type](intune_deviceconfig_deviceplatformtype.md)
- [Device threat protection level](intune_deviceconfig_devicethreatprotectionlevel.md)
- [Diagnostic data submission mode](intune_deviceconfig_diagnosticdatasubmissionmode.md)
- [Domain name source](intune_deviceconfig_domainnamesource.md)
- [Eap fast configuration](intune_deviceconfig_eapfastconfiguration.md)
- [Eap type](intune_deviceconfig_eaptype.md)
- [EAS authentication method](intune_deviceconfig_easauthenticationmethod.md)
- [EAS email profile configuration base](intune_deviceconfig_easemailprofileconfigurationbase.md)
- [Edge cookie policy](intune_deviceconfig_edgecookiepolicy.md)
- [Edge search engine](intune_deviceconfig_edgesearchengine.md)
- [Edge search engine base](intune_deviceconfig_edgesearchenginebase.md)
- [Edge search engine custom](intune_deviceconfig_edgesearchenginecustom.md)
- [Edge search engine type](intune_deviceconfig_edgesearchenginetype.md)
- [Edition upgrade configuration](intune_deviceconfig_editionupgradeconfiguration.md)
- [Edition upgrade license type](intune_deviceconfig_editionupgradelicensetype.md)
- [Email sync duration](intune_deviceconfig_emailsyncduration.md)
- [Email sync schedule](intune_deviceconfig_emailsyncschedule.md)
- [Extended key usage](intune_deviceconfig_extendedkeyusage.md)
- [Firewall certificate revocation list check method type](intune_deviceconfig_firewallcertificaterevocationlistcheckmethodtype.md)
- [Firewall packet queueing method type](intune_deviceconfig_firewallpacketqueueingmethodtype.md)
- [Firewall pre shared key encoding method type](intune_deviceconfig_firewallpresharedkeyencodingmethodtype.md)
- [Folder protection type](intune_deviceconfig_folderprotectiontype.md)
- [Hash algorithms](intune_deviceconfig_hashalgorithms.md)
- [Ink access setting](intune_deviceconfig_inkaccesssetting.md)
- [Intended purpose](intune_deviceconfig_intendedpurpose.md)
- [Internet site security level](intune_deviceconfig_internetsitesecuritylevel.md)
- [iOS bookmark](intune_deviceconfig_iosbookmark.md)
- [iOS certificate profile](intune_deviceconfig_ioscertificateprofile.md)
- [iOS certificate profile base](intune_deviceconfig_ioscertificateprofilebase.md)
- [iOS compliance policy](intune_deviceconfig_ioscompliancepolicy.md)
- [iOS custom configuration](intune_deviceconfig_ioscustomconfiguration.md)
- [iOS device features configuration](intune_deviceconfig_iosdevicefeaturesconfiguration.md)
- [iOS EAS email profile configuration](intune_deviceconfig_ioseasemailprofileconfiguration.md)
- [iOS EDU certificate settings](intune_deviceconfig_ioseducertificatesettings.md)
- [iOS EDU device configuration](intune_deviceconfig_iosedudeviceconfiguration.md)
- [iOS education device configuration](intune_deviceconfig_ioseducationdeviceconfiguration.md)
- [iOS enterprise Wi-Fi configuration](intune_deviceconfig_iosenterprisewificonfiguration.md)
- [iOS general device configuration](intune_deviceconfig_iosgeneraldeviceconfiguration.md)
- [iOS home screen app](intune_deviceconfig_ioshomescreenapp.md)
- [iOS home screen folder](intune_deviceconfig_ioshomescreenfolder.md)
- [iOS home screen folder page](intune_deviceconfig_ioshomescreenfolderpage.md)
- [iOS home screen item](intune_deviceconfig_ioshomescreenitem.md)
- [iOS home screen page](intune_deviceconfig_ioshomescreenpage.md)
- [iOS imported PFX certificate profile](intune_deviceconfig_iosimportedpfxcertificateprofile.md)
- [iOS network usage rule](intune_deviceconfig_iosnetworkusagerule.md)
- [iOS notification alert type](intune_deviceconfig_iosnotificationalerttype.md)
- [iOS notification settings](intune_deviceconfig_iosnotificationsettings.md)
- [iOS PKCS certificate profile](intune_deviceconfig_iospkcscertificateprofile.md)
- [iOS SCEP certificate profile](intune_deviceconfig_iosscepcertificateprofile.md)
- [iOS single sign on settings](intune_deviceconfig_iossinglesignonsettings.md)
- [iOS trusted root certificate](intune_deviceconfig_iostrustedrootcertificate.md)
- [iOS update configuration](intune_deviceconfig_iosupdateconfiguration.md)
- [iOS update device status](intune_deviceconfig_iosupdatedevicestatus.md)
- [iOS updates install status](intune_deviceconfig_iosupdatesinstallstatus.md)
- [iOS VPN configuration](intune_deviceconfig_iosvpnconfiguration.md)
- [iOS web content filter auto-filter](intune_deviceconfig_ioswebcontentfilterautofilter.md)
- [iOS web content filter base](intune_deviceconfig_ioswebcontentfilterbase.md)
- [iOS web content filter specific websites access](intune_deviceconfig_ioswebcontentfilterspecificwebsitesaccess.md)
- [iOS Wi-Fi configuration](intune_deviceconfig_ioswificonfiguration.md)
- [Key size](intune_deviceconfig_keysize.md)
- [Key storage provider option](intune_deviceconfig_keystorageprovideroption.md)
- [Key usages](intune_deviceconfig_keyusages.md)
- [Key value](intune_deviceconfig_keyvalue.md)
- [Local security options administrator elevation prompt behavior type](intune_deviceconfig_localsecurityoptionsadministratorelevationpromptbehaviortype.md)
- [Local security options format and eject of removable media allowed user type](intune_deviceconfig_localsecurityoptionsformatandejectofremovablemediaallowedusertype.md)
- [Local security options information displayed on lock screen type](intune_deviceconfig_localsecurityoptionsinformationdisplayedonlockscreentype.md)
- [Local security options information shown on lock screen type](intune_deviceconfig_localsecurityoptionsinformationshownonlockscreentype.md)
- [Local security options smart card removal behavior type](intune_deviceconfig_localsecurityoptionssmartcardremovalbehaviortype.md)
- [Local security options standard user elevation prompt behavior type](intune_deviceconfig_localsecurityoptionsstandarduserelevationpromptbehaviortype.md)
- [macOS certificate profile base](intune_deviceconfig_macoscertificateprofilebase.md)
- [macOS compliance policy](intune_deviceconfig_macoscompliancepolicy.md)
- [macOS custom configuration](intune_deviceconfig_macoscustomconfiguration.md)
- [macOS device features configuration](intune_deviceconfig_macosdevicefeaturesconfiguration.md)
- [macOS endpoint protection configuration](intune_deviceconfig_macosendpointprotectionconfiguration.md)
- [macOS enterprise Wi-Fi configuration](intune_deviceconfig_macosenterprisewificonfiguration.md)
- [macOS firewall application](intune_deviceconfig_macosfirewallapplication.md)
- [macOS gatekeeper app sources](intune_deviceconfig_macosgatekeeperappsources.md)
- [macOS general device configuration](intune_deviceconfig_macosgeneraldeviceconfiguration.md)
- [macOS imported PFX certificate profile](intune_deviceconfig_macosimportedpfxcertificateprofile.md)
- [macOS SCEP certificate profile](intune_deviceconfig_macosscepcertificateprofile.md)
- [macOS trusted root certificate](intune_deviceconfig_macostrustedrootcertificate.md)
- [macOS VPN configuration](intune_deviceconfig_macosvpnconfiguration.md)
- [macOS Wi-Fi configuration](intune_deviceconfig_macoswificonfiguration.md)
- [Managed device certificate state](intune_deviceconfig_manageddevicecertificatestate.md)
- [Managed device reported app](intune_deviceconfig_manageddevicereportedapp.md)
- [Media content rating Australia](intune_deviceconfig_mediacontentratingaustralia.md)
- [Media content rating Canada](intune_deviceconfig_mediacontentratingcanada.md)
- [Media content rating France](intune_deviceconfig_mediacontentratingfrance.md)
- [Media content rating Germany](intune_deviceconfig_mediacontentratinggermany.md)
- [Media content rating Ireland](intune_deviceconfig_mediacontentratingireland.md)
- [Media content rating Japan](intune_deviceconfig_mediacontentratingjapan.md)
- [Media content rating New Zealand](intune_deviceconfig_mediacontentratingnewzealand.md)
- [Media content rating United Kingdom](intune_deviceconfig_mediacontentratingunitedkingdom.md)
- [Media content rating United States](intune_deviceconfig_mediacontentratingunitedstates.md)
- [Miracast channel](intune_deviceconfig_miracastchannel.md)
- [NDES connector](intune_deviceconfig_ndesconnector.md)
- [NDES connector state](intune_deviceconfig_ndesconnectorstate.md)
- [Non eap authentication method for eap ttls type](intune_deviceconfig_noneapauthenticationmethodforeapttlstype.md)
- [Non eap authentication method for peap](intune_deviceconfig_noneapauthenticationmethodforpeap.md)
- [Number range](intune_deviceconfig_numberrange.md)
- [OMA setting](intune_deviceconfig_omasetting.md)
- [OMA setting base64](intune_deviceconfig_omasettingbase64.md)
- [OMA setting boolean](intune_deviceconfig_omasettingboolean.md)
- [OMA setting date time](intune_deviceconfig_omasettingdatetime.md)
- [OMA setting floating point](intune_deviceconfig_omasettingfloatingpoint.md)
- [OMA setting integer](intune_deviceconfig_omasettinginteger.md)
- [OMA setting string](intune_deviceconfig_omasettingstring.md)
- [OMA setting string xml](intune_deviceconfig_omasettingstringxml.md)
- [Operating system version range](intune_deviceconfig_operatingsystemversionrange.md)
- [Policy platform type](intune_deviceconfig_policyplatformtype.md)
- [Prerelease features](intune_deviceconfig_prereleasefeatures.md)
- [Rating apps type](intune_deviceconfig_ratingappstype.md)
- [Rating Australia movies type](intune_deviceconfig_ratingaustraliamoviestype.md)
- [Rating Australia television type](intune_deviceconfig_ratingaustraliatelevisiontype.md)
- [Rating Canada movies type](intune_deviceconfig_ratingcanadamoviestype.md)
- [Rating Canada television type](intune_deviceconfig_ratingcanadatelevisiontype.md)
- [Rating France movies type](intune_deviceconfig_ratingfrancemoviestype.md)
- [Rating France television type](intune_deviceconfig_ratingfrancetelevisiontype.md)
- [Rating Germany movies type](intune_deviceconfig_ratinggermanymoviestype.md)
- [Rating Germany television type](intune_deviceconfig_ratinggermanytelevisiontype.md)
- [Rating Ireland movies type](intune_deviceconfig_ratingirelandmoviestype.md)
- [Rating Ireland television type](intune_deviceconfig_ratingirelandtelevisiontype.md)
- [Rating Japan movies type](intune_deviceconfig_ratingjapanmoviestype.md)
- [Rating Japan television type](intune_deviceconfig_ratingjapantelevisiontype.md)
- [Rating New Zealand movies type](intune_deviceconfig_ratingnewzealandmoviestype.md)
- [Rating New Zealand television type](intune_deviceconfig_ratingnewzealandtelevisiontype.md)
- [Rating United Kingdom movies type](intune_deviceconfig_ratingunitedkingdommoviestype.md)
- [Rating United Kingdom television type](intune_deviceconfig_ratingunitedkingdomtelevisiontype.md)
- [Rating United States movies type](intune_deviceconfig_ratingunitedstatesmoviestype.md)
- [Rating United States television type](intune_deviceconfig_ratingunitedstatestelevisiontype.md)
- [Required password type](intune_deviceconfig_requiredpasswordtype.md)
- [Restricted apps state](intune_deviceconfig_restrictedappsstate.md)
- [Restricted apps violation](intune_deviceconfig_restrictedappsviolation.md)
- [Safe search filter type](intune_deviceconfig_safesearchfiltertype.md)
- [Secure assessment account type](intune_deviceconfig_secureassessmentaccounttype.md)
- [Setting source](intune_deviceconfig_settingsource.md)
- [Setting state device summary](intune_deviceconfig_settingstatedevicesummary.md)
- [Shared PC account deletion policy type](intune_deviceconfig_sharedpcaccountdeletionpolicytype.md)
- [Shared PC account manager policy](intune_deviceconfig_sharedpcaccountmanagerpolicy.md)
- [Shared PC allowed account type](intune_deviceconfig_sharedpcallowedaccounttype.md)
- [Shared PC configuration](intune_deviceconfig_sharedpcconfiguration.md)
- [Sign in assistant options](intune_deviceconfig_signinassistantoptions.md)
- [Site security level](intune_deviceconfig_sitesecuritylevel.md)
- [Software update status summary](intune_deviceconfig_softwareupdatestatussummary.md)
- [State management setting](intune_deviceconfig_statemanagementsetting.md)
- [Subject alternative name type](intune_deviceconfig_subjectalternativenametype.md)
- [Subject name format](intune_deviceconfig_subjectnameformat.md)
- [Unsupported device configuration](intune_deviceconfig_unsupporteddeviceconfiguration.md)
- [Unsupported device configuration detail](intune_deviceconfig_unsupporteddeviceconfigurationdetail.md)
- [Update classification](intune_deviceconfig_updateclassification.md)
- [User email source](intune_deviceconfig_useremailsource.md)
- [Username source](intune_deviceconfig_usernamesource.md)
- [Visibility setting](intune_deviceconfig_visibilitysetting.md)
- [VPN authentication method](intune_deviceconfig_vpnauthenticationmethod.md)
- [VPN DNS rule](intune_deviceconfig_vpndnsrule.md)
- [VPN on demand rule](intune_deviceconfig_vpnondemandrule.md)
- [VPN on demand rule connection action](intune_deviceconfig_vpnondemandruleconnectionaction.md)
- [VPN on demand rule connection domain action](intune_deviceconfig_vpnondemandruleconnectiondomainaction.md)
- [VPN proxy server](intune_deviceconfig_vpnproxyserver.md)
- [VPN route](intune_deviceconfig_vpnroute.md)
- [VPN server](intune_deviceconfig_vpnserver.md)
- [VPN traffic rule](intune_deviceconfig_vpntrafficrule.md)
- [VPN traffic rule app type](intune_deviceconfig_vpntrafficruleapptype.md)
- [VPN traffic rule routing policy type](intune_deviceconfig_vpntrafficruleroutingpolicytype.md)
- [Web browser cookie settings](intune_deviceconfig_webbrowsercookiesettings.md)
- [Weekly schedule](intune_deviceconfig_weeklyschedule.md)
- [Welcome screen meeting information](intune_deviceconfig_welcomescreenmeetinginformation.md)
- [Wi-Fi authentication method](intune_deviceconfig_wifiauthenticationmethod.md)
- [Wi-Fi proxy setting](intune_deviceconfig_wifiproxysetting.md)
- [Wi-Fi security type](intune_deviceconfig_wifisecuritytype.md)
- [Windows 10 app type](intune_deviceconfig_windows10apptype.md)
- [Windows 10 associated apps](intune_deviceconfig_windows10associatedapps.md)
- [Windows 10 certificate profile base](intune_deviceconfig_windows10certificateprofilebase.md)
- [Windows 10 compliance policy](intune_deviceconfig_windows10compliancepolicy.md)
- [Windows 10 custom configuration](intune_deviceconfig_windows10customconfiguration.md)
- [Windows 10 EAS email profile configuration](intune_deviceconfig_windows10easemailprofileconfiguration.md)
- [Windows 10 edition type](intune_deviceconfig_windows10editiontype.md)
- [Windows 10 endpoint protection configuration](intune_deviceconfig_windows10endpointprotectionconfiguration.md)
- [Windows 10 enterprise modern app management configuration](intune_deviceconfig_windows10enterprisemodernappmanagementconfiguration.md)
- [Windows 10 general configuration](intune_deviceconfig_windows10generalconfiguration.md)
- [Windows 10 imported PFX certificate profile](intune_deviceconfig_windows10importedpfxcertificateprofile.md)
- [Windows 10 mobile compliance policy](intune_deviceconfig_windows10mobilecompliancepolicy.md)
- [Windows 10 network boundary configuration](intune_deviceconfig_windows10networkboundaryconfiguration.md)
- [Windows 10 network proxy server](intune_deviceconfig_windows10networkproxyserver.md)
- [Windows 10 PFX import certificate profile](intune_deviceconfig_windows10pfximportcertificateprofile.md)
- [Windows 10 PKCS certificate profile](intune_deviceconfig_windows10pkcscertificateprofile.md)
- [Windows 10 secure assessment configuration](intune_deviceconfig_windows10secureassessmentconfiguration.md)
- [Windows 10 team general configuration](intune_deviceconfig_windows10teamgeneralconfiguration.md)
- [Windows 10 VPN authentication method](intune_deviceconfig_windows10vpnauthenticationmethod.md)
- [Windows 10 VPN configuration](intune_deviceconfig_windows10vpnconfiguration.md)
- [Windows 10 VPN connection type](intune_deviceconfig_windows10vpnconnectiontype.md)
- [Windows 10 VPN profile target](intune_deviceconfig_windows10vpnprofiletarget.md)
- [Windows 10 VPN proxy server](intune_deviceconfig_windows10vpnproxyserver.md)
- [Windows 8.1 certificate profile base](intune_deviceconfig_windows81certificateprofilebase.md)
- [Windows 8.1 compliance policy](intune_deviceconfig_windows81compliancepolicy.md)
- [Windows 8.1 general configuration](intune_deviceconfig_windows81generalconfiguration.md)
- [Windows 8.1 SCEP certificate profile](intune_deviceconfig_windows81scepcertificateprofile.md)
- [Windows 8.1 trusted root certificate](intune_deviceconfig_windows81trustedrootcertificate.md)
- [Windows 8.1 VPN configuration](intune_deviceconfig_windows81vpnconfiguration.md)
- [Windows 8.1 VPN proxy server](intune_deviceconfig_windows81vpnproxyserver.md)
- [Windows 8.1 Wi-Fi import configuration](intune_deviceconfig_windows81wifiimportconfiguration.md)
- [Windows assigned access profile](intune_deviceconfig_windowsassignedaccessprofile.md)
- [Windows certificate profile base](intune_deviceconfig_windowscertificateprofilebase.md)
- [Windows defender advanced threat protection configuration](intune_deviceconfig_windowsdefenderadvancedthreatprotectionconfiguration.md)
- [Windows delivery optimization mode](intune_deviceconfig_windowsdeliveryoptimizationmode.md)
- [Windows firewall network profile](intune_deviceconfig_windowsfirewallnetworkprofile.md)
- [Windows kiosk active directory group](intune_deviceconfig_windowskioskactivedirectorygroup.md)
- [Windows kiosk app base](intune_deviceconfig_windowskioskappbase.md)
- [Windows kiosk app configuration](intune_deviceconfig_windowskioskappconfiguration.md)
- [Windows kiosk autologon](intune_deviceconfig_windowskioskautologon.md)
- [Windows kiosk Azure AD group](intune_deviceconfig_windowskioskazureadgroup.md)
- [Windows kiosk Azure AD user](intune_deviceconfig_windowskioskazureaduser.md)
- [Windows kiosk configuration](intune_deviceconfig_windowskioskconfiguration.md)
- [Windows kiosk desktop app](intune_deviceconfig_windowskioskdesktopapp.md)
- [Windows kiosk local group](intune_deviceconfig_windowskiosklocalgroup.md)
- [Windows kiosk local user](intune_deviceconfig_windowskiosklocaluser.md)
- [Windows kiosk multiple apps](intune_deviceconfig_windowskioskmultipleapps.md)
- [Windows kiosk profile](intune_deviceconfig_windowskioskprofile.md)
- [Windows kiosk single UWP app](intune_deviceconfig_windowskiosksingleuwpapp.md)
- [Windows kiosk user](intune_deviceconfig_windowskioskuser.md)
- [Windows kiosk UWP app](intune_deviceconfig_windowskioskuwpapp.md)
- [Windows kiosk visitor](intune_deviceconfig_windowskioskvisitor.md)
- [Windows network isolation policy](intune_deviceconfig_windowsnetworkisolationpolicy.md)
- [Windows Phone 8.1 certificate profile base](intune_deviceconfig_windowsphone81certificateprofilebase.md)
- [Windows Phone 8.1 compliance policy](intune_deviceconfig_windowsphone81compliancepolicy.md)
- [Windows Phone 8.1 custom configuration](intune_deviceconfig_windowsphone81customconfiguration.md)
- [Windows Phone 8.1 general configuration](intune_deviceconfig_windowsphone81generalconfiguration.md)
- [Windows Phone 8.1 imported PFX certificate profile](intune_deviceconfig_windowsphone81importedpfxcertificateprofile.md)
- [Windows Phone 8.1 SCEP certificate profile](intune_deviceconfig_windowsphone81scepcertificateprofile.md)
- [Windows Phone 8.1 trusted root certificate](intune_deviceconfig_windowsphone81trustedrootcertificate.md)
- [Windows Phone 8.1 VPN configuration](intune_deviceconfig_windowsphone81vpnconfiguration.md)
- [Windows phone EAS email profile configuration](intune_deviceconfig_windowsphoneeasemailprofileconfiguration.md)
- [Windows privacy data access control item](intune_deviceconfig_windowsprivacydataaccesscontrolitem.md)
- [Windows privacy data access level](intune_deviceconfig_windowsprivacydataaccesslevel.md)
- [Windows privacy data category](intune_deviceconfig_windowsprivacydatacategory.md)
- [Windows spotlight enablement settings](intune_deviceconfig_windowsspotlightenablementsettings.md)
- [Windows start menu app list visibility type](intune_deviceconfig_windowsstartmenuapplistvisibilitytype.md)
- [Windows start menu mode type](intune_deviceconfig_windowsstartmenumodetype.md)
- [Windows update active hours install](intune_deviceconfig_windowsupdateactivehoursinstall.md)
- [Windows update for business configuration](intune_deviceconfig_windowsupdateforbusinessconfiguration.md)
- [Windows update for business update weeks](intune_deviceconfig_windowsupdateforbusinessupdateweeks.md)
- [Windows update insider build control](intune_deviceconfig_windowsupdateinsiderbuildcontrol.md)
- [Windows update install schedule type](intune_deviceconfig_windowsupdateinstallscheduletype.md)
- [Windows update scheduled install](intune_deviceconfig_windowsupdatescheduledinstall.md)
- [Windows update type](intune_deviceconfig_windowsupdatetype.md)
- [Windows user account control settings](intune_deviceconfig_windowsuseraccountcontrolsettings.md)
- [Windows VPN configuration](intune_deviceconfig_windowsvpnconfiguration.md)
- [Windows VPN connection type](intune_deviceconfig_windowsvpnconnectiontype.md)