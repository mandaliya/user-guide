# Audio Anonymization

The **Audio** anonymization feature allows you to listen to sample audio scenarios and see how anonymization is applied to sensitive data. Currently, real-time anonymization testing for audio is not available, but you can explore different sample scenarios in the demo.

## How to Use the Audio Anonymization Feature

1. **Select Sample Scenario**:  
   Choose from various pre-defined audio scenarios available in the dropdown. Example scenarios include:
   - **Healthcare Call**: Anonymize sensitive information in a healthcare conversation.
   - **Customer Support**: Anonymize sensitive customer data during support calls.
   - **Legal Consultation**: Anonymize sensitive information shared during legal consultations.

2. **Listen to the Audio**:  
   After selecting a scenario, you can play the sample audio. The audio player lets you listen to the scenario and understand how the anonymization process works.

3. **Convert to Text**:  
   Once you've listened to the sample audio, you can click the **Convert to Text** button to convert the audio into text format. This allows you to view the anonymized text data that corresponds to the audio.

4. **Select Anonymization Method**:  
   You can choose an anonymization method to apply to the text after conversion. The available methods are:
   - **Replace**: Replace detected entities with a placeholder (e.g., “******”).
   - **Redact**: Completely hide detected sensitive information (e.g., “REDACTED”).
   - **Mask**: Mask the detected information by replacing characters with a specific symbol (e.g., “*****”).
   - **Tokenization**: Replace sensitive information with a token, which is a randomly generated identifier that can be later mapped back to the original data.
   - **Encryption**: Encrypt the detected sensitive data so it is stored in a secure format, only accessible with a decryption key.
   - **Pseudonymization**: Replace sensitive data with pseudonyms, ensuring that the data cannot be traced back to an individual without additional information.
   - **Hash**: Hash the detected data, turning it into a fixed-size string that represents the original data, but cannot be reverted back to the original value.

5. **Allow List**:  
   The **Allow List** feature lets you specify entities that should not be anonymized, even if they are detected. Enter any terms or values you wish to keep intact in the **Allow List**.

6. **Deny List**:  
   The **Deny List** ensures that certain entities are always anonymized, regardless of whether they are detected automatically. Add items to the **Deny List** to force their anonymization.

7. **Select Entities to Detect**:  
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

8. **Apply Anonymization**:  
   Once everything is configured, click the **Apply Anonymization** button to process the text and anonymize the detected entities according to your selected anonymization method.

---

While real-time audio anonymization isn't available yet, this demo will give you a great idea of how the tool processes sensitive audio data for anonymization and privacy compliance.

