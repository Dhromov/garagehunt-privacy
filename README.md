# Privacy Policy for GarageHunt

**Effective Date:** November 1, 2026  
**Last Updated:** November 1, 2026

This Privacy Policy describes how **GarageHunt** ("we", "our", or "the App") collects, uses, and shares your information when you use our mobile application.

---

### 1. Information We Collect

To provide our core services — discovering, listing, and receiving alerts for nearby garage sales — we may collect and process the following information:

* **Location Data:**
  * **Approximate and Precise Location (Foreground):** We collect your device's GPS and location data while the App is open to display your location on the map, center listings around you, set notification alert radiuses, and calculate directions. We do not track your location in the background when the App is closed.
* **Photos and Images:**
  * If you create a garage sale listing, the App accesses your camera and/or photo gallery with your permission to allow you to upload images (3–5 photos) depicting the sale items. 
  * Uploaded photos are scanned via automated content moderation systems (Google Cloud Vision API) solely to detect inappropriate or disallowed content before publication.
* **Listing Content:**
  * Details you submit, such as event addresses, descriptions, operating hours, and approximate price ranges.
* **Device and Diagnostic Information:**
  * **FCM Token:** An anonymous Firebase Cloud Messaging token is generated to deliver push notifications about newly listed sales within your configured radius.
  * Device identifiers, crash logs, and performance data collected automatically by third-party SDKs.

---

### 2. Third-Party Services and Advertising

We integrate trusted third-party services that may collect information used to identify or deliver relevant services to you:

* **Google Play Services:** Fundamental app runtime services.
* **Google Maps Platform:** Interactive mapping, geocoding, and map rendering.
* **Firebase (Google LLC):**
  * *Firebase Cloud Firestore & Storage:* Storing listing metadata and compressed listing images.
  * *Firebase Cloud Messaging (FCM):* Delivering real-time sale alert notifications.
* **Google AdMob:**
  * We use Google AdMob to display banner advertisements.
  * AdMob may collect and use advertising identifiers (AAID), cookies, and device telemetry to serve personalized or non-personalized ads in compliance with applicable advertising laws.
  * You can review Google's advertising privacy terms at: [Google Ad Policies](https://policies.google.com/technologies/ads).

---

### 3. How We Use Your Information

We use the collected information for the following purposes:
* Displaying active garage sales on the interactive map.
* Publishing and managing your garage sale listings.
* Sending push notifications when a new sale is published within your selected radius.
* Preventing prohibited, offensive, or fraudulent listings via automated image and text moderation.
* Serving banner advertisements to support ongoing App maintenance.

---

### 4. Data Sharing and Retention

* **Public Visibility:** When you publish a listing, the photos, descriptions, hours, prices, and address you provide become publicly visible to other GarageHunt users on the map.
* **Automatic Expiration:** All listing data and associated photos are automatically deleted from our servers upon reaching the specified end date of the event.
* **Sale / Transfer:** We do not sell, rent, or trade your personal information or location history to any third parties.

---

### 5. Permissions Requested

* `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`: To center the map and locate nearby garage sales.
* `POST_NOTIFICATIONS`: To deliver alerts about nearby garage sales.
* `CAMERA` / `READ_MEDIA_IMAGES`: To allow uploading photos for your listings.

You may revoke any of these permissions at any time through your Android device settings.

---

### 6. Children's Privacy

GarageHunt is not directed to individuals under the age of 13 (or under 16 where applicable by law). We do not knowingly collect personal information from children. If we become aware that a child has provided us with personal information, we take immediate steps to delete such data.

---

### 7. User Rights and Data Deletion

You retain full control over your content:
* You can remove your listing at any time directly within the App via the **"Manage My Listing"** screen by tapping **"Delete / Cancel Sale"**.
* To request manual deletion of any associated data or FCM tokens, please contact us at the support email provided below.

---

### 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted within the App or on this page with an updated effective date.

---

### 9. Contact Us

If you have questions or concerns regarding this Privacy Policy, please contact us at:  
**Email:** dhromov.dev@gmail.com  
**Developer:** GarageHunt
