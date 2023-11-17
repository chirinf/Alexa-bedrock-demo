# Alexa Skill for Image Generation with Amazon Bedrock

## B) Create S3 Bucket:
    1.- Go to AWS Console and create a new bucket.
    
## B) Create Lambda Layers:
    1.- Boto3-mlayer (arn:aws:lambda:us-east-1:770693421928:layer:Klayers-p38-Pillow:7)
    2.- Klayers-p38-Pillow (zip in repo)
    3.- ASK_CORE_P38 (zip in repo)

## C) Create Lambda Function:
    1.- Create function alexa_txt2img_skill_dl_bedrock (code in repo)
    2.- Add permision to function role (included in IAM folder)

## C) Assing policies to lambda role:
    1.- Open the lambda role, create the policie (in policies|txt2img-bedrock). Replace with the correct bucket.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.