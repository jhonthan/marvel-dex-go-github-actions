
## 💡 Idea
In this project the idea is based in the code in Go get the names and informations about the Marvel Comics using the Marvel API.

---

### 🛠️ Worked with
+ [Azure](https://portal.azure.com/)
    + [Web-App](https://azure.microsoft.com/en-us/products/app-service/web)
+ [Marvel API](https://developer.marvel.com/)
+ [GitHub](https://www.github.com)
    + [GitHub-Actions](https://www.github.com/features/actions)
    + [GitHub-Actions-Marketplace](https://github.com/marketplace)
    + [Azure Web-App](https://github.com/marketplace/actions/azure-webapp)
---

### 🚀 Process

1. Define the secrets in GitHub project:
 - `MARVEL_PUBLIC_KEY` = Public Key based in the subscription in Marvel API.
 - `MARVEL_PRIVATE_KEY` = Private Key based in the subscription in Marvel API.


### ⌛ Testing the result

1. After the creation of Azure Web-App, is posible to test the appication using Default domain: `Your-APP.azurewebsites.net`

### 📂 Diagram

![Diagrams](./diagrams/pipeline.drawio.png)

Code Based in the repo: (https://github.com/KubeDev/marvel-dex)