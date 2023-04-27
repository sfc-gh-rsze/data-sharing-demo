# data-sharing-demo

There are 3 files for this demo:
1. demo - direct share (provider)
2. demo - broker 1 (customer)
3. demo - broker 2 (customer)

- You will need 2 snowflake account for this demo. One as a provider and one as a consumer. 
- You will use file #1 to set up the share as a provider. In this demo, it uses 3 different methods to share covering regular table, row access policy and reader account. You can choose whichever you want to demo. 
- For share #1, you will use file #2 to run at the consumer account.
- For share #2, you will use file #3 to run at the same consumer account. They will use different database name.
- For share #3, you will use reader account to look at the data.
