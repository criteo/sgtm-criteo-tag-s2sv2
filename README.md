# Server-side Google Tag Manager Criteo Tag for S2S v2

The purpose of this Tag is to forward the web events directly to Criteo servers when triggered from the Google Tag Manager server-container, directly to Criteo servers.
Please note that no formatting is done on the events, it simply forwards the events it receives, while adding some fields.

* **crto_fpid** 

# Installation

> :warning: **This server template is supposed to work alongside** [Criteo Client Tag for S2S v2](https://github.com/criteo/gtm-criteo-client-s2sv2) which needs to be installed on your Google Tag Manager web-container!

Please get in touch with your Criteo contact to fill the following parameters: 

* **applicationId** (which is used to identify and properly format your event in Criteo format on our end, recommended format for this field is ***com.advertiserName.sgtm***)
* **partnerId**
