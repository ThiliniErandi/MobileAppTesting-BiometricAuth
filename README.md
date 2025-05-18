# 📲 Mobile Biometric Authentication Manual Testing

This repository documents a comprehensive manual QA process for mobile biometric authentication features across Android and iOS platforms. The testing process ensures high reliability, functionality, and security for the biometric login experience, with a focus on different device states, user types, and authentication scenarios.

---

## 🧪 Test Coverage Overview

### 1. **Settings Screen**  
- **Biometric Availability**  
   - Ensure the biometric toggle option appears in the settings list if the biometric is available on the device.
   - If biometric authentication is not supported or enabled on the device, the toggle should be hidden.
  
- **Biometric Options**  
   - iOS: Touch ID, Face ID  
   - Android: Fingerprint, Face ID, or both.

- **UI/UX Testing**  
   - Check the correct visibility of the biometric toggle and ensure appropriate labels are displayed.
   - Validate success or failure messages when enabling or disabling biometric authentication.
  
### 2. **App Lifecycle Events**  
- **Install/Uninstall/Reinstall**  
   - Test biometric settings persistence after app install/uninstall/reinstall.
  
- **App Updates**  
   - Ensure that the app properly maintains the biometric settings during upgrades.

- **Permission Changes**  
   - Test biometric authentication behavior when the user changes device-level biometric permissions.

### 3. **User Authentication & Session Management**  
- **Logged-in Users**  
   - Test biometric login for users who are logged in with valid credentials.

- **Auto-logout Scenarios**  
   - Test scenarios where the user is auto-logged out due to session expiration or manual logout.

- **Password Reset & Re-enable Biometric Auth**  
   - Verify if biometric authentication is enabled after a password reset, if applicable.

### 4. **Multi-Device and Multi-User Testing**  
- **Multiple Devices**  
   - Ensure a user can use biometric authentication across multiple devices.

- **Shared Devices**  
   - Test biometric authentication on shared devices used by multiple users.

### 5. **Notification Behavior**  
- **Login Prompt**  
   - Verify the biometric prompt appears upon app launch or after session expiration.

- **Fallback Behavior**  
   - Ensure users can revert to credential-based login if biometric authentication fails or is canceled.

### 6. **Device Compatibility**  
- **iOS & Android**  
   - Ensure compatibility across a variety of devices, including those with fingerprint and Face ID support.

- **Operating System Versions**  
   - Test on a range of OS versions for both Android and iOS.

### 8. **Performance Testing**  
- **Response Time**  
   - Measure the time it takes from launching the app to successfully authenticating via biometric methods.

- **Battery & Memory Usage**  
   - Evaluate the app’s impact on battery and memory during repeated biometric authentications.

---

## 🛠️ Tools & Platforms Used
- Android & iOS Devices
- Manual Test Execution

---

## 📎 Notes
This repository focuses on general QA practices for biometric authentication. No confidential, proprietary, or company-specific data is included. All test cases and observations aim to showcase typical QA methodologies and testing techniques.

---

👩‍💻 Author  
**Thilini Kumarawadu**  
QA Engineer | Mobile App Testing | Passionate about edge-case exploration 🚀
