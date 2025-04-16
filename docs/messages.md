# Messages Anonymization

The **Messages** anonymization feature allows you to anonymize message data in a simulated mobile screen. You can type your own messages, and the tool will anonymize any detected sensitive information automatically.

## How to Use the Messages Anonymization Feature

1. **Type Your Message**:  
   In the simulated mobile screen, type your message content into the input field. The anonymization tool will process the message and detect any sensitive data as you type.

2. **Select Anonymization Method**:  
   After typing your message, you can select the anonymization method to apply to the detected entities. The available methods include:
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
   You can choose which types of sensitive information you want the tool to detect and anonymize in the message. If you want to anonymize all sensitive entities, leave **No selection** checked. If you only want to anonymize specific types of data (e.g., credit cards, email addresses), select the appropriate entities.

   Available entities to detect include:
   - **Credit Card**
   - **Crypto**
   - **Payment Information**
   - **Date/Time**
   - **Email Address**
   - **IBAN Code**
   - **IP Address**
   - **National Registration Number**

6. **Show Analysis Explanations**:  
   You can enable **Analysis Explanations** to view how each detected entity was recognized and its confidence score.

7. **Apply Anonymization**:  
   Once everything is configured, click the **Apply Anonymization** button to process the message content. The tool will replace the detected entities according to your selected anonymization method.

---

By using the **Messages** anonymization feature, you can ensure that sensitive data within your messages is protected while maintaining the structure and flow of the conversation on the mobile interface.
