# Support Ticket Anonymization

The **Support Ticket** anonymization feature allows you to anonymize sensitive information while creating support tickets. This ensures that no confidential information is exposed in your support tickets while maintaining the ticket's structure.

## How to Use the Support Ticket Anonymization Feature

1. **Create Support Ticket**:  
   - **Subject**: Enter the subject of the support ticket.
   - **Description**: Write the description of the issue you are reporting. The anonymization tool will automatically detect and anonymize sensitive data as you type.

2. **Select Anonymization Method**:  
   After composing the ticket, you can select the anonymization method to apply to the detected entities. Available anonymization methods include:
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
   You can choose which types of sensitive information you want the tool to detect and anonymize in the support ticket. If you want to anonymize all sensitive entities, leave **No selection** checked. If you only want to anonymize specific types of data (e.g., credit cards, email addresses), select the appropriate entities.

   Available entities to detect include:
   - **Credit Card**
   - **Crypto**
   - **Payment Information**
   - **Date/Time**
   - **Email Address**
   - **IBAN Code**
   - **IP Address**
   - **National Registration Number**

6. **Load Sample**:  
   You can click the **Load Sample** button to load a sample support ticket for anonymization. This helps you test the anonymization process with predefined data.

7. **Show Analysis Explanations**:  
   You can enable **Analysis Explanations** to view how each detected entity was recognized and its confidence score.

8. **Apply Anonymization**:  
   Once everything is configured, click the **Apply Anonymization** button to process the support ticket. The tool will replace the detected entities according to your selected anonymization method.

---

By using the **Support Ticket** anonymization feature, you can ensure that sensitive data within your tickets is protected, helping you maintain privacy while interacting with customer support teams.
