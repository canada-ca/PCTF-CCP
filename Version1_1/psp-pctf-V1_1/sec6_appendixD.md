<a name="sec6"></a>

<div class="breaker"></div>

## 6 <a name="APPENDIX D"></a>APPENDIX D: IDENTITY AND CREDENTIAL VERIFICATION 

This appendix provides some additional background information on the nature of identity verification and credential verification.

### 6.1 Identity Verification

Identity Verification is the process of confirming that the identity information is under the control of the Subject. It should be noted that this process may use personal information or organizational information that is not related to identity. There are 4 methods used to achieve identity verification:

> **Knowledge-based confirmation:** An identity verification method that uses personal or organizational information or shared secrets to prove that the person or organization presenting the identity information is in control of the identity. Knowledge-based confirmation is achieved by means of the challenge- response model: the person or organization presenting the identity information is asked questions, the answers to which (in theory, at least) only they and the interrogator would know (e.g., financial information, credit history, shared secret, cryptographic key, mailed-out access code, password, personal identification number, assigned identifier).
> 
> **Biological or behavioural characteristic confirmation:** An identity verification method that uses biological (anatomical and physiological) characteristics (e.g., face, fingerprints, retinas) or behavioural characteristics (e.g., keyboard stroke timing, gait) to prove that the person presenting the identity information is in control of the identity. Biological or behavioural characteristic confirmation is achieved by means of the challenge-response model: the biological or behavioural characteristics recorded on a document or in a data store are compared to the person presenting the identity information
> 
> **Physical possession confirmation:** An identity verification method that requires physical possession or presentation of evidence to prove that the person or organization presenting the identity information is in control of the identity.
> 
> **Trusted referee confirmation:** An identity verification method that relies on a trusted referee to prove that the person or organization presenting the identity information is in control of the identity. The type of trusted referee and their acceptability is determined by program-specific criteria. Examples of trusted referees include guarantors, notaries, accountants, and certified agents.

### 6.2 Credential Verification

Credential Verification is the process of verifying that a Holder has control over an issued credential. Control of an issued credential is verified by means of one or more authenticators. The degree of control over the issued credential and the status of the issued credential (i.e., not tampered with, corrupted, modified, suspended, or revoked) can be used to generate a level of assurance. The Credential Verification process is also used to prove that the Holder is the same entity as the entity in the previous transaction.

The Credential Verification process is dependent on the **Credential-Authenticator Binding** process:

> **Credential-Authenticator Binding**: The process of associating a credential issued to a Holder with one or more authenticators.
> 
> An authenticator is something that a Holder controls that is used to prove that the Holder has retained control over an issued credential. There are 3 types of authenticators:
> 
> * Something the Holder has (e.g., a cryptographic key or a one-time- password). This is similar to physical possession confirmation used by Identity Verification.
> * Something the Holder knows (i.e., knowledge-based authenticators [KBAs]) (e.g., a password, a response to a challenge question). This is similar to knowledge-based confirmation used by Identity Verification.
> * Something the Holder is or does (e.g., face, fingerprints, retinas, keyboard stroke timing, gait). This is similar to biological or behavioural characteristic confirmation used by Identity Verification.
> 
> The Credential-Authenticator Binding process also includes authenticator life- cycle activities such as suspending authenticators (caused by a forgotten password or a lockout due to successive failed authentications, inactivity, or suspicious activity), removing authenticators, binding new authenticators, and updating authenticators (e.g., changing a password, updating security questions and answers, having a new facial photo taken).


