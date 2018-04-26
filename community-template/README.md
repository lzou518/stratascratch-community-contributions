![strata scratch](visualizations/sslogo.jpg) 
# Strata Scratch Community Template Guidelines
Thank you for your interest in contributing your data analyses to our community repository! This template is aimed at helping you upload your work to our repo.

## Guidelines for folder/file structure
1. Name your repo anything you'd like but be sure to include the table name you used in your analysis for reference. For example, if you analyzed datasets.yelp_reviews, then your repo might be called "An analysis of yelp_reviews".

2. The README.md file is where your questions, code, visualizations, and answers are placed. At a minimum, it should include:
    * the names of the database table(s) being analyzed
    * a description of the dataset
    * questions and analytical topics
    * code
    * visualizations
3. Save your graphs in a folder named "visualizations". Your visualizations should be linked to the README.md, using markdown language. 
    * When naming your folder and files be sure to only use lower case letters and numbers. Do not use capital letters, spaces, or symbols.

## Instructions on formatting and style
1. Formatting headers, bulletpoints, etc. can be found in the [Markdown Style Guide](https://guides.github.com/features/mastering-markdown/).
2. To embed your code, you will also need to use Markdown language found in the [guide](https://guides.github.com/features/mastering-markdown/). It should look something like this:

```sql
SELECT * FROM datasets.yelp_reviews
```

3. To link your visualizations, your images need to be in .jpg, .png, or some other image format and placed into the "visualizations" folder. You will then link the image in the README.md by specifying the path to the image. 
     * A guide to markdown language can be found [here](https://guides.github.com/features/mastering-markdown/), but briefly in order to link an image in markdown language, follow the syntax below:

```markdown
![name of image](folder name/image name.jpg)
```

## Ready to contribute to the community
1. When you're ready to upload your data analysis to the community, follow the guide on the main page of the [community repository](https://github.com/stratascratch/stratascratch-community-contributions)
  
## References
- Markdown Style Guide (https://guides.github.com/features/mastering-markdown/)
- An example of a good repo (https://github.com/LisaDziuba/Marketing-for-Engineers#-social-media-marketing)
- An another example of a good repo (https://github.com/rasbt/biopandas)

Questions? Comments? Feel free to email us at team@stratascratch.com
