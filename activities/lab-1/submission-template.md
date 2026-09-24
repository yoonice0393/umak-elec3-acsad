# Lab 1 Submission

## Part B
**Error Action Name:** You are not authorized to perform this operation. User: arn:aws:iam::548387266019:user/acsad-g07 is not authorized to perform: ec2:CreateSecurityGroup on resource: arn:aws:ec2:ap-southeast-1:548387266019:security-group/* because no identity-based policy allows the ec2:CreateSecurityGroup action. Encoded authorization failure message: 6hgnuYqJ5CQayXBsXknkI67agacB6ZgQ-KgIcGFsxq0PNyFf36_WAYUUAyN_6QuC9pGyVFjpCMnOMNeL777xQafYCFEOeeQeXouFBFcBPafVyVjpBwcfY_Ru8ZiNtpyMy38KZpnqBm6NBD5PO0Cypv1G2YZoFfgugfJx3vHKqkk6CUWuzy25DUuCdIYiVsAOFNFfqefJXb8lKeXNkWfJnFtj22jjFOJHFhir8FTu2zYxTE1uOI5NRMwy82gWZ35F7jdrsLmQjLx1s_3nUawgzfMPQg9jHKilsYktTz9MC1V72Q2AETrVaJPCXr80vvxr00X7N8HP64jVzUaqBEtgSVabfCaovE0-UBn7jQMr7ss-FBozvper96mVEXWzNWuXXTay8N1eYP9J7gfd1CzeQZCIWgHeWmZlVkE1NhzKimVIb-Wot95SVULiFh8Us4MxqwAlIIipdUc62UGOQ0W9PxqeuAFoqKIQcFjIv10a-u_qBr62efpnt1JDYOSqostB9JFaSehx0F0iO_w23L2n_CFTsWwHiEpNBDUIcNsk 

**Screenshot (Part B launch denial with username visible):**
![Part B Error](part-b-error.png)

## Part C
**Policy Statement Blanks:**
- `"Action"`: <answer>
- `"Resource"`: <answer>
- `"ec2:InstanceType"`: <answer>

## Part D
**Security Group Error Text:** <paste error text>

**Running Instance Time:** <write time here>

**Screenshot 1 (Permissions tab listing <user>-launch):**
![Permissions Tab](part-d-policy.png)

**Screenshot 2 (Instance in Running state):**
![Running Instance](part-d-instance.png)

## Part E
**t3.small / Tokyo Denial Error:** <paste error text>

**Screenshot 1 (t3.small or Tokyo denial):**
![Boundary Denial](part-e-denial.png)

**Screenshot 2 (CloudTrail event showing errorMessage):**
![CloudTrail Event](part-e-cloudtrail.png)

## Part F Questions
1. Which action did the Part B error name?
   <answer>
2. In your policy, which condition limits `ec2:RunInstances`?
   <answer>
3. After you attached `ec2:*` on `*`, why was `t3.small` still denied? Name the boundary statement.
   <answer>
4. Why is `ec2:*` on `*` a poor policy even with a boundary?
   <answer>
5. In two sentences: what does the boundary control that your policy cannot?
   <answer>
