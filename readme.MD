REGION_CODE=us-east-1 
CLUSTER_NAME=expense 
ACC_ID=308731954939

* OIDC PROVIDER
'''
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
'''