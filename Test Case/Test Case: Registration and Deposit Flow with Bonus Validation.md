# Test Case: Registration and Deposit Flow - Mobile Web

---

## Basic Information:
- **TestCaseID:** TC-REG-001
- **Tester:** Ana Rodrigues
- **Priority:** High
- **Severity (if bug found)**: High
- **Test Type:** Functional
- **Date Executed:** 04/17/2025
- **Environment:** Apple iPhone 15 Pro - iOS 17.5.1, Safari Browser
- **Build Version:** 2025.00

---

## Preconditions:
- Tester must be physically located in the United Kingdom.
- Tester must not have existing accounts with related brands.
- Tester must use real information for registration.
- Tester must use the test_username format (example: `test_anarod`).
- Tester must be prepared to make a minimum £10 deposit.

---

## Steps to Execute:

### Step 1: Registration
1. Start screen recording.
2. Navigate to the platform's official registration site (URL provided separately).
3. Complete the registration using a unique test_username format.
4. Verify mobile number.
5. Fill in occupation details upon reaching the platform.
6. Confirm landing on the homepage.
7. Stop the recording.

### Step 2: Deposit + Bonus
1. Start a new screen recording.
2. Open the Cashier/Deposit section.
3. Deposit a minimum of £10 using any available payment method.
4. Enter the bonus code: `----` in the Bonus Code field.
5. Confirm that the deposit is successful and balance updates.
6. Check for a pop-up confirming receipt of 100 Free Spins.
7. If the pop-up does not appear, re-login and check Rewards manually.
8. Navigate to Rewards from the Menu → Sidebar → Rewards.
9. Launch the associated game and verify the presence of free spins.
10. Capture screenshots showing Rewards and Bonus.

### Step 3: Attachments
1. Attach a screenshot showing device information.
2. Attach a screenshot of your location settings.

---

## Expected Result
- User is able to successfully register.
- Deposit is successful.
- Bonus (100 Free Spins) is correctly credited and visible under Rewards.
- User can launch the game and utilize the free spins.

---

## Actual Result (Failed)
- User is able to register and deposit successfully.
- Bonus pop-up did not appear automatically after the deposit.
- Free spins were not reflected in the Rewards section nor in the game.

---

## Post-Conditions
- User remains logged in.
- Balance updated correctly after deposit.
- Bonus not granted automatically.

---

## Evidence
- Registration Video (`Registration.mp4`)
- Deposit Video (`Deposit_PayPal.mp4`)
- Screenshot of Rewards section (`Rewards.jpeg`)
- Screenshot of Game Bonus (`Selected_Game.PNG`)
- Screenshot of Device Information (`Device_info.jpeg`)
- Screenshot of Location Verification (`Location.jpeg`)


