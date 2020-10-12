# Appsync Intro

## Helpful Documentation

-   [Cloudformation: Appsync GraphQL Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-graphqlapi.html)

-   [Cloudformation: Appsync Schema Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-graphqlschema.html)

-   [Cloudformation: Appsync API KEY Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-apikey.html)

-   [Cloudformation: Appsync Datasource Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-datasource.html)

-   [Cloudformation: Appsync Resolver Resource](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-appsync-resolver.html)

-   [VTL: Resolver Mapping Template Reference](https://docs.aws.amazon.com/appsync/latest/devguide/resolver-mapping-template-reference.html)

## Intructions

-   `sam build`
-   `sam deploy --guided`

We will have to change the capabilities setting in our toml file to:
`capabilities = "CAPABILITY_NAMED_IAM"`
