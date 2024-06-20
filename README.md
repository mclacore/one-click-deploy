# one-click-deploy
Azure one click deploy button

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmclacore%2Fone-click-deploy%2Fmain%2Ftemplate.json)

Step to update button:
1. Fetch raw URL for JSON file in GitHub
2. Use a URL encoder to encode URL
3. Append URL to end of `[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/<here>)`
