Ask the client for these items:

**Firebase**
- Firebase project access with **Owner** or at least permissions for Hosting, Firestore, Auth, Storage, Functions, and Secret Manager.
- Confirmation that the project is on **Blaze/pay-as-you-go**.
- Firebase project ID.
- Firebase web app config.
- Permission to enable:
  - Authentication: Anonymous + Email/password
  - Firestore
  - Storage
  - Cloud Functions
  - Hosting
  - Secret Manager

**Admin**
- Admin/staff email to create or use for `/admin/`.
- Temporary admin password, or ask them to create the user in Firebase Auth.
- Approval to set custom claim `admin: true` for that user.

**Razorpay**
- Razorpay **Key ID**.
- Razorpay **Key Secret**.
- Confirm whether keys are **Test mode** or **Live mode**.
- Razorpay account/business name to show in checkout if needed.

**Domain**
- Domain/DNS access for `annamay.in`, or whoever manages DNS.
- Confirm final live domain: `annamay.in` / `www.annamay.in`.
- Permission to connect domain to Firebase Hosting.

**Restaurant settings**
- Open/closed status for launch.
- GST percentage.
- Delivery radius.
- Restaurant latitude/longitude.
- Delivery fee rules.
- Google review link.
- Phone number and address to show publicly.

**Assets**
- Final logo/icon if they have one.
- Final restaurant photos / OG image.
- Any menu images they want uploaded.

You can send them this simple message:

```text
Please share Firebase project access, Razorpay keys, admin email, domain/DNS access, and final restaurant settings so I can connect the live website, deploy Cloud Functions, enable payments, and make the admin/order system work end to end.
```
