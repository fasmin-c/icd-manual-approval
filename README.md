
# CI/CD Pipeline with Manual Approval

This project uses GitHub, AWS CodeBuild, and AWS CodePipeline.

## Pipeline Stages
1. Source - GitHub
2. Build - AWS CodeBuild
3. Manual Approval - Maintainer reviews and approves changes

The pipeline pauses at the Manual Approval stage and resumes after approval.
