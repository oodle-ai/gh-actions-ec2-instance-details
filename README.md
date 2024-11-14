# gh-actions-ec2-instance-details
GitHub Action Step to show EC2 instance details and connection information 

We need this to be in a separate repository of its own
because we want to be able to run this step even before
the checkout step. [Local actions require checkout to run before them](
https://github.com/orgs/community/discussions/26245#discussioncomment-3250935).

The alternative would've been to copy-paste a 40-line script in
each workflow file, making it unweildy.

<img width="1322" alt="image" src="https://github.com/user-attachments/assets/85724e7b-2689-4f67-8d3b-f99084ac51bc">
