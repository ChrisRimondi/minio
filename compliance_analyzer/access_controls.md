# Access Controls.Md

```json
{
  "implemented-requirements": [
    {
      "uuid": "e7b9f5c1-6d8c-4c0f-bc9b-3b9ac5eae8a7",
      "control-id": "IAC-01.3",
      "description": "The system maintains a current list of authorized users and service accounts through automated mechanisms that regularly synchronize with the LDAP directory. This ensures that any changes in user status are promptly reflected in the system, allowing for effective management of user access."
    },
    {
      "uuid": "d60c9c5b-2d9f-4e61-9a17-3f4aef1e1a5b",
      "control-id": "IAC-02",
      "description": "The software uniquely identifies and centrally authenticates organizational users through integration with the LDAP system, which validates user credentials against stored entries. This mechanism also includes authorization checks to ensure users have the appropriate permissions to access resources."
    },
    {
      "uuid": "cb4f4d0e-6b78-4cbb-9d6c-6e2504d7c4b3",
      "control-id": "IAC-02.2",
      "description": "Automated mechanisms for replay-resistant authentication are implemented by utilizing security tokens that include timestamps and unique identifiers. The system checks the validity of these tokens against a storage mechanism to prevent replay attacks."
    },
    {
      "uuid": "a1e5c1ae-3d43-4b9e-b1b8-4b3c734e5e9d",
      "control-id": "IAC-03",
      "description": "The implementation uniquely identifies and centrally authenticates third-party users through a service account management process that validates access tokens against predefined policies, ensuring that access is granted only to authorized external entities."
    },
    {
      "uuid": "f3e4f72f-2e45-4cbb-9b3d-2e3e3c72d8b3",
      "control-id": "IAC-04",
      "description": "The system implements mechanisms for device identification and authentication through bidirectional authentication, which verifies both the device and user credentials before establishing a connection."
    },
    {
      "uuid": "bcf3b9a3-4a47-4d1b-bb2d-08fbd8e23f5e",
      "control-id": "IAC-04.1",
      "description": "Device identification and authentication is accurately managed by centrally controlling the joining of devices to the domain through a secure configuration management process that includes validation of device credentials."
    },
    {
      "uuid": "e5c9d3d5-7d6e-48d5-a3b4-0e6a1c4e6c0f",
      "control-id": "IAC-06",
      "description": "Multi-Factor Authentication (MFA) is enforced through automated mechanisms that require users to provide additional verification for remote access and critical systems, ensuring that only authenticated users can access sensitive data."
    },
    {
      "uuid": "3b3f6c34-a5d6-4f1c-b4a3-1c6eab3b8e1c",
      "control-id": "IAC-08",
      "description": "Role-Based Access Control (RBAC) is enforced through policies that restrict access based on user roles and permissions, ensuring that only authorized users can access sensitive/regulated data as per their assigned roles."
    },
    {
      "uuid": "5e6c3b9a-9f6b-4f4e-bc3a-5d9e9a3c1c2f",
      "control-id": "IAC-13.1",
      "description": "The system provides a Single Sign-On (SSO) capability to streamline authentication for users across various applications, ensuring a seamless user experience while maintaining security."
    },
    {
      "uuid": "cbffec98-8f09-4b2a-8b4b-9e3f5b5f4c0a",
      "control-id": "IAC-16",
      "description": "Privileged Account Management (PAM) is enforced through strict policies that limit and control privileged access rights, ensuring that only authorized personnel can access sensitive administration functions."
    },
    {
      "uuid": "2f3c0a76-5e2c-4e4a-9f9d-d2c9a0e7f1e9",
      "control-id": "IAC-20",
      "description": "Logical Access Control (LAC) permissions are enforced through mechanisms that adhere to the principle of least privilege, ensuring users have only the necessary access rights required to perform their tasks."
    },
    {
      "uuid": "c9f5c0c3-4a8b-4b7f-9b1d-0f9defb2a0be",
      "control-id": "IAC-21",
      "description": "The system utilizes the principle of least privilege by limiting user access to only those processes necessary for their job functions, thereby minimizing the risk of unauthorized access to sensitive data."
    },
    {
      "uuid": "b9b85c75-e1b5-4f54-9c77-5c1b75d8a1b5",
      "control-id": "IAC-21.3",
      "description": "The assignment of privileged accounts is restricted to management-approved personnel through a controlled approval process, ensuring that only designated individuals have elevated access rights."
    },
    {
      "uuid": "d1fd7c13-8e48-4e2f-8d09-4c1d8c0e8b4b",
      "control-id": "IAC-22",
      "description": "The system enforces account lockout mechanisms that limit consecutive invalid login attempts and automatically lock accounts after reaching a predefined threshold, enhancing security against brute force attacks."
    },
    {
      "uuid": "bcf7e7b0-5de2-4ac7-8a74-5f4d1a57c9e8",
      "control-id": "IAC-23",
      "description": "The number of concurrent sessions for each system account is limited to prevent excessive access and potential abuse, ensuring that user sessions are appropriately managed."
    },
    {
      "uuid": "ab0f5c3c-7c5e-4c36-9f5c-0c4e2e2e3b6b",
      "control-id": "IAC-29",
      "description": "Attribute-Based Access Control (ABAC) is enforced through a dynamic policy-driven approach that evaluates user attributes and contextual information to grant access, supporting secure information sharing."
    }
  ]
}
```