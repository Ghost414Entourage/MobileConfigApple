Use the command uuidgen for the profile after each < key > PayloadUUID < /key>

![Gemini_Generated_Image_7q8lra7q8lra7q8l](https://github.com/user-attachments/assets/b19a441a-7c63-4ce2-91b0-4955b2563a80)

The difference between using <string>System</string> and <integer>1</integer> in the context of mobileconfig files relates to their purpose and the kind of information they represent:

<string>System</string>

- Purpose: This key indicates the scope of the configuration profile. In this case, it specifies that the profile applies at the system level, meaning it affects all users on the device rather than just a single user or a specific group.
  
- Usage: This is commonly used for policies that need to be enforced across the entire device, such as security settings, network configurations, or application restrictions.

<integer>1</integer>

- Purpose: This typically denotes the version of the payload or configuration profile. The value 1 usually indicates that this is the first version of the payload.
  
- Usage: This is useful for version control, helping to manage changes and updates to configuration profiles over time. If a profile is updated, the version number would increment to reflect that.
