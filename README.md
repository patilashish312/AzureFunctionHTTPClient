# AzureFunctionHTTPClient

In this project, I have utilized spring boot based adaptor for building java based Azure function.
This will help in terms of using singleton HTTPClient instance in java Azure function instead of creating instances per request.

As of current, there is no built in feature in java azure function which will be used for creating singleton instance , hence we need to use
spring framework adaptor.

