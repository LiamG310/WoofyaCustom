# WoofyaCustom
Description: Final model, development code and relevant database files for the custom recommendation system with GPT insights.

Directions: 
  1. Ensure all files are in the same directory and check that inputs match outputs where necessary.
  2. Run 'WoofyaCustomInsights.ipynb' first using the a cleaned .csv version of the dataset Rhys sent us. Running this generates the insights the GPT API was about to take from the dataset [Note: requires GPT API key, available through OpenAI]. If you need to explore the raw data further this is the place. Brief instructions given in file.
  3. Run 'WoofyaCustomDev.ipynb'. This is where I developed the recommendation system.
  4. Run 'WoofyaCustom.ipynb', the final model of the 'in-house' recommendation system. This file can be used with the generated .csv to provide comprehensive recommendations.

Note: Weightings are applied to the recommendation model in 'WoofyaCustom.ipynb' to balance more fairly between distance and search preference. Feel free to change the weighting values.
Note: All three WoofyaCustom files are jupyter notebook files as this format is useful for exploration, however they can all easily be converted to Python files to be implemented as a script. 
