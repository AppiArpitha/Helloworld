Keep naming convention, everything same, okay? And then just again copy the code from the GRSNA flow repo for this creation of secret or those thing, okay? And create a new secret. That's fine. Like, so what happened now? When you created a new secret, the secrets are remain same, okay? Like the values should remain same, GRSNA and that GTS one. Only difference is it's created a new secret, okay? Can you repeat again once again, please? So, so one thing, from GRSNA, this particular flow GRSNA, NA1, from that artifact, copy the secrets to your GTS artifact, okay? First thing, copy means, means, like you have to create a secret on your cloud flow artifact. First part, okay? Second part. So, you do it manually, right, that one you are saying? Secrets you have to create it manually itself, for GRSNA also, the secrets is static only, not a dynamic. If you check the secret, then you got to know the secrets are static only. So once you got the actual value for GTS source, okay, then you directly replace those values in your secret. Okay? Okay? So first part is this secret creation here in that artifact. Second part is, like where you do, like, do the changes for the retrieving the secrets or those things. Revert back those changes to the existing one. Existing one means the GRSNA one, okay? GTS one. No, no. So, first part is secret creation here in that GTS. second part is, like in your code, you are retrieving the secret from secret manager. Correct? For now. That you have to revert back to the original one. Okay. Okay? And then just try to create it. Okay? Once you, like, copy the secret and revert where that code, third part is, you have to generate a new authentication code. Huh, from here, no? Okay, once you do with all the code changes, then generate a new code, execute a pipeline, paste that code in that particular parameter, and let me know whether it worked or not. Okay, sure. I'll do it.
Here’s a clean, step-by-step version of what was explained, keeping everything consistent and easy to follow:

---
 Step 1: Create Secrets in GTS Artifact
Follow the same naming convention as used in GRSNA (don’t change anything).
Go to your GTS flow artifact.
Manually create new secrets (same as GRSNA).
Copy the values exactly from GRSNA (they are static, not dynamic).
Only difference → new secret is created, values remain the same.


---
 Step 2: Copy Values from GRSNA
From GRSNA (NA1 flow artifact):
Identify the required secrets.
Copy their actual values.

Paste those values into the newly created GTS secrets.


---
 Step 3: Revert Code Changes
In your code, you are currently retrieving secrets (probably modified earlier).
Revert this logic back to the original implementation (same as GRSNA flow).
Do NOT keep any temporary/custom changes you made for testing.


---
 Step 4: Generate Authentication Code
After code + secret setup is done:
Generate a new authentication code.



---
 Step 5: Run Pipeline
Trigger the pipeline.
Paste the generated auth code into the required parameter.
Execute the flow.


---
 Final Check
Verify whether the flow is working correctly.
If not, check:
Secret names (must match exactly)
Secret values (no mismatch)
Code reverted properly



---
If you want, I can convert this into a proper message or documentation format you can send to your team.
