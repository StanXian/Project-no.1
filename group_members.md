Charlotte, Stan, Bryan!

Our Process: 

1. We searched for Google's list of public API's and decided to use their Custom Search API
https://console.developers.google.com/apis/library/customsearch.googleapis.com?q=Custom&id=4b0c5e50-0a7a-46cc-84f4-5aabeaebf6f2&project=adwordsreportingapppython&organizationId=304985908845
They have lots of documentation and example projets to refer to.

2. From the Custom Search API, we clicked "Try This API" and it lead us here:
https://developers.google.com/apis-explorer/?hl=en_US#p/customsearch/v1/

Then it directed us to Google's plug and play API Explorer (this is an amazing place)
https://developers.google.com/apis-explorer/?hl=en_US#p/customsearch/v1/search.cse.siterestrict.list

3. It also supplied the url that we can use in our JSON/Jupyter Notebook code ~HOLLA~ 
https://www.googleapis.com/customsearch/v1?q=kermit&cx=000783178101923127511%3Avw462omy5uo&exactTerms=kermit&key={YOUR_API_KEY}

4. But before moving forward we needed to set up our API key and an engine ID
API – https://developers.google.com/custom-search/v1/overview
Engine ID – https://support.google.com/customsearch/answer/2649143

And we had to follow this documentation on setting up a custom search engine
https://developers.google.com/custom-search/docs/tutorial/creatingcse

5. After setting up the API and the engine ID we had access to more Google developer tools such as
  
  • A congratulations page with links to our custom search engine
  https://cse.google.com/cse/create/congrats?cx=000783178101923127511%3Avw462omy5uo
  
  • This is the direct link to the public custom search engine home page 
  https://cse.google.com/cse?cx=000783178101923127511:vw462omy5uo & https://cse.google.com/all
  
  • Here's additional documentation on setting up a custom search https://support.google.com/customsearch/answer/4513886?visit_id=636862323078982551-1909578757&rd=1
  
6. We also have to install the Google Client Python Libraries
https://developers.google.com/api-client-library/python/start/installation 
