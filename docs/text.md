# Text Anonymization

The **Text** anonymization feature allows you to anonymize sensitive information within text input. You can enter text, select anonymization methods, choose entities to detect, and then apply the anonymization process to ensure sensitive data is protected.

## How to Use the Text Anonymization Feature

1. **Enter Text to Anonymize**:  
   In the text box, paste or type the text that you want to anonymize. The tool will detect sensitive information such as credit card numbers, email addresses, and more.

2. **Select Anonymization Method**:  
   After entering your text, you can select the anonymization method you prefer. The available methods include:
   - **Replace**: Replace detected entities with a placeholder (e.g., “******”).
   - **Redact**: Completely hide detected sensitive information (e.g., “REDACTED”).
   - **Mask**: Mask the detected information by replacing characters with a specific symbol (e.g., “*****”).
   - **Tokenization**: Replace sensitive information with a token, which is a randomly generated identifier that can be later mapped back to the original data.
   - **Encryption**: Encrypt the detected sensitive data so it is stored in a secure format, only accessible with a decryption key.
   - **Pseudonymization**: Replace sensitive data with pseudonyms, ensuring that the data cannot be traced back to an individual without additional information.
   - **Hash**: Hash the detected data, turning it into a fixed-size string that represents the original data, but cannot be reverted back to the original value.

3. **Allow List**:  
   The **Allow List** feature lets you specify entities that should not be anonymized, even if they are detected. Enter any terms or values you wish to keep intact in the **Allow List**.

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
   Once everything is configured, click the **Apply Anonymization** button to process the text. The tool will replace the detected entities according to your selected anonymization method.

## Additional Options
- **Enable Analysis Explanations**:  
   You can choose to enable this feature to view how each detected entity was recognized and its confidence score.

---

By using the **Text** anonymization feature, you can effectively ensure that sensitive data within textual content is protected, helping you maintain privacy compliance and safeguard personal information.
