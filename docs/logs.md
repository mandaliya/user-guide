# Log Anonymization

The **Logs** anonymization feature allows you to anonymize log entries while preserving their structure. This ensures that sensitive information in logs is protected without compromising the integrity and readability of the log files.

## How to Use the Log Anonymization Feature

1. **Paste Log Entries**:  
   In the provided text box, paste the log entries that you want to anonymize. You can also click the **Load Sample Log** button to load a sample log and anonymize it.

2. **Select Anonymization Method**:  
   After entering your log data, you can choose an anonymization method. The available options are:
   - **Replace**: Replace detected entities with a placeholder (e.g., “******”).
   - **Redact**: Completely hide detected sensitive information (e.g., “REDACTED”).
   - **Mask**: Mask the detected information by replacing characters with a specific symbol (e.g., “*****”).
   - **Tokenization**: Replace sensitive information with a token, which is a randomly generated identifier that can be later mapped back to the original data.
   - **Encryption**: Encrypt the detected sensitive data so it is stored in a secure format, only accessible with a decryption key.
   - **Pseudonymization**: Replace sensitive data with pseudonyms, ensuring that the data cannot be traced back to an individual without additional information.
   - **Hash**: Hash the detected data, turning it into a fixed-size string that represents the original data, but cannot be reverted back to the original value.

3. **Allow List**:  
   The **Allow List** lets you specify entities that should not be anonymized, even if they are detected. Add any terms or values you wish to keep intact in the **Allow List**.

4. **Deny List**:  
   The **Deny List** ensures that certain entities are always anonymized, regardless of whether they are detected automatically. Add items to the **Deny List** to force their anonymization.

5. **Select Entities to Detect**:  
   You can choose which types of sensitive information you want the tool to detect and anonymize. If you want to anonymize all sensitive entities, leave **No selection** checked. If you only want to anonymize specific types of data (e.g., credit cards, email addresses), select the appropriate entities.

   Available entities to detect include:
   - **Credit Card**
   - **Crypto**
   - **Payment Information**
   - **Date/Time**
   - **Email Address**
   - **IBAN Code**
   - **IP Address**
   - **National Registration Number**

6. **Apply Anonymization**:  
   Once everything is configured, click the **Apply Anonymization** button to process the log entries. The tool will replace the detected entities according to your selected anonymization method.

---

By using the **Log** anonymization feature, you can protect sensitive data in log files while preserving the overall structure, which is crucial for ongoing system monitoring and troubleshooting.
