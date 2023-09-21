- 👋 Hi, I’m @RAJ1443
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
RAJ1443/RAJ1443 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
find the inputs ) reports structure>> 
inbuild_text_'information' 
stale:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/stale@v8
        with:
          stale-issue-message: 'This issue is stale because it has been open 60 days with no activity. Remove stale label or comment or this will be closed in 10 days.'
          stale-pr-message: 'This PR is stale because it has been open 60 days with no activity. Remove stale label or comment or this will be closed in 10 days.'
          close-issue-message: 'This issue was closed because it has been stalled for 10 days with no activity.'
          close-pr-message: 'This PR was closed because it has been stalled for 10 days with no activity.'
          days-before-issue-stale: 60
          days-before-pr-stale: 60
          days-before-issue-close: 10
          days-before-pr-close: 10 
          
