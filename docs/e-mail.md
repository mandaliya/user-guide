# Email Anonymization

The **Email** anonymization feature allows you to compose an email and automatically anonymize sensitive information in the email before it is sent. This feature helps ensure that any sensitive data shared in the email is properly protected.

## How to Use the Email Anonymization Feature

1. **Compose the Email**:  
   - **To**: Enter the recipient’s email address.
   - **Subject**: Add a subject for your email.
   - **Body**: Write the content of your email.

2. **Select Anonymization Method**:  
   After composing the email, you can select the anonymization method to apply to detected entities. The available methods include:
   - **Replace**: Replace detected entities with a placeholder (e.g., “******”).
   - **Redact**: Completely hide detected sensitive information (e.g., “REDACTED”).
   - **Mask**: Mask the detected information by replacing characters with a specific symbol (e.g., “*****”).
   - **Tokenization**: Replace sensitive information with a token, which is a randomly generated identifier that can be later mapped back to the original data.
   - **Encryption**: Encrypt the detected sensitive data so it is stored in a secure format, only accessible with a decryption key.
   - **Pseudonymization**: Replace sensitive data with pseudonyms, ensuring that the data cannot be traced back to an individual without additional information.
   - **Hash**: Hash the detected data, turning it into a fixed-size string that represents the original data, but cannot be reverted back to the original value.

3. **Allow List**:  
   The **Allow List** lets you specify entities that should not be anonymized, even if they are detected. Add any terms or values you want to keep intact in the **Allow List**.

4. **Deny List**:  
   The **Deny List** ensures that certain entities are always anonymized, regardless of whether they are detected automatically. Add items to the **Deny List** to force their anonymization.

5. **Select Entities to Detect**:  
   Choose which types of sensitive information you want to detect and anonymize in the email. You can choose to anonymize:
   - **Credit Card**
   - **Crypto**
   - **Payment Information**
   - **Date/Time**
   - **Email Address**
   - **IBAN Code**
   - **IP Address**
   - **National Registration Number**

   If you want to anonymize all detected entities, leave **No selection** checked. To anonymize specific entities, select the ones you want.

6. **Show Anonymization Preview**:  
   If you'd like to see a preview of how your email will look after anonymization, check the **Show Anonymization Preview** option. This lets you view the anonymized email content before sending.

7. **Apply Anonymization and Send Email**:  
   Once everything is configured, click the **Apply Anonymization and Send Email** button to anonymize the email content and send it to the recipient.

---

By using the **Email** anonymization feature, you can ensure that sensitive information shared in emails is protected, helping you comply with privacy regulations while maintaining communication security.
