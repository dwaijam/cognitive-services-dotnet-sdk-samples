# Quickstart for Personalizer API with C# 
<a name="HOLTop"></a>

This sample demonstrates how to use the [Personalizer APIs](https://azure.microsoft.com/en-us/services/cognitive-services/personalizer/) with C# to perform the following actions:

* Rank a list of actions for personalization.
* Report reward to allocate to the top ranked action based on user selection for the specified event.

The code was written to work on a .Net Core application, with minimal references to external libraries, so you could also run it on Linux or MacOS.

Refer to the [API definitions](https://westus2.dev.cognitive.microsoft.com/docs/services/personalizer-api/operations/Rank) for technical documentation for the APIs.

## Prerequisites

You must have a [Cognitive Services API account](https://docs.microsoft.com/azure/cognitive-services/cognitive-services-apis-create-account) with **Personalizer API**. You can use the **free tier for 5,000 transactions/month** to complete this quickstart.

You must also have the [endpoint and access key](https://github.com/Azure/personalization-rl/blob/master/docs/how-to-configure.md#get-your-personalization-api-key) that was generated for you during sign up.

## Running the project

1. Open the PersonalizerExample.sln file in Visual Studio 2017.
2. Replace the subscription key stub with the key you obtain from your free account.
3. Ensure that region is set to the Azure region associated with the free account.
4. Run the solution.