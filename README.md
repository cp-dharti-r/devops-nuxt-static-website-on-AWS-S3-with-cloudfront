# Deploy Nuxt static website on AWS S3 with Cloudfront

### The Website will run on the Cloudfront domain name

- Created SPA using a Static-site generator in Nuxt 3
- Project has CI/CD to Generate a static website and deploy it on AWS S3
- Deployment file also managed creation/updation of cloudformation stack and cloudfront distribution along with OAC(Origin Access Control) for clodfront to manage your website

### Requirements

- nodeJs (18 or above)
- npm (latest stable version)
- nuxt basic knowledge
- AWS s3, cloudformation, clodfront basic knowledge
- Set secrets to your repository
  - `AWS_REGION` (AWS region)
  - `AWS_ACCESS_KEY_ID` (AWS access key id)
  - `AWS_SECRET_ACCESS_KEY` (AWS secret access key)
  - `AWS_BUCKET_NAME` (AWS s3 bucket name)
  - `AWS_IAM_USER` (IAM userid) (ex, 39xxxxxxxx08)
