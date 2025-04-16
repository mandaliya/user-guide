# Document Anonymization

The **Document** anonymization feature allows you to upload various document formats (e.g., TXT, DOCX, PDF) and anonymize sensitive information within them. The tool automatically processes the document and applies the selected anonymization methods to protect sensitive data.

## How to Use the Document Anonymization Feature

1. **Upload Document**:  
   To start, click on the **Choose files** button to upload a document. Supported file formats include:
   - **TXT**
   - **DOCX**
   - **PDF**

   Please ensure that the file size is under 10MB.

2. **Select Anonymization Method**:  
   After uploading your document, you can select the anonymization method you prefer. The available methods include:
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
   Once everything is configured, click the **Apply Anonymization** button to process the document. The tool will replace the detected entities according to your selected anonymization method.

---

By using the **Document** anonymization feature, you can easily anonymize sensitive information within your documents and ensure data privacy and compliance with relevant regulations.
