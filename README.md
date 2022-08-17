# featureflag-demo
Steps:
- Download this index.html file
- Navigate to file and run on your browser
- Create a project in LaunchDarkly using the Javascript SDK
- Create a feature flag called "ColorBox"
- In the index.html replace the environment-specific key to your own (line 41)

In LaunchDarkly:
- if "ColorBox" flag is toggled off, expect to see a "say goodbye" button and "yes" and "no" buttons NOT working
- if "ColorBox" flag is toggled on, expect to see a "say hello" button and "yes" and "no" buttons to work
