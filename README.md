<div align="center">
  <img src="img/logo.svg" alt="death note" style="height: 80px; width: 80px; padding: 0 20px;">
  <h1>Death Note</h1>
  <p>A tribute and log of beloved African products and services that failed.</p>
</div>

<div align="center">

</div>

## Contribute

To add a product, gather the following information:

- Name of Product (`name`)
- Launch Year (`dateOpen`)
- Discontinued Year (`dateClose`)
- Description (`description`)
- Country (`country`)

If you are already familiar with `git`, follow these steps:

1. If you haven't already, start by [forking](https://help.github.com/en/articles/fork-a-repo) this repository. 
2. [Create a new branch](https://help.github.com/en/desktop/contributing-to-projects/creating-a-branch-for-your-work) in your fork. Name it using the product you want to add 
3. Switch to that branch (should happen automatically if you've just created it) and open the `deathnote.json` file
4. Use the information gathered above to add a JSON entry in the following format:
```
  {
    "dateClose": "YYYY",
    "dateOpen": "YYYY",
    "description": "[Product Name] was a single sentence overview of the product or service.",
    "name": "[Product Name]",
    "country": "Country",
  }
```
5. Finally, [create a Pull Request (PR)](https://help.github.com/en/articles/creating-a-pull-request) using the newly created branch (Important: DON'T use the `master` branch for the PR). Submit it with the necessary explanations.  
