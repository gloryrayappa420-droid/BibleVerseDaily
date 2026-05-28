# BibleVerseDaily
A Beautiful Android app displaying inspiring bible verses daily on the lock screen with aesthetic design
# Create project directory
mkdir BibleVerseDaily
cd BibleVerseDaily

# Initialize git
git init
git branch -M main

# Add remote (replace USERNAME with your GitHub username)
git remote add origin https://github.com/gloryrayappa420-droid/BibleVerseDaily.git

# Pull initial files if you added README
git pull origin main --allow-unrelated-histories 2>/dev/null || true

# Create the directory structure
mkdir -p app/src/main/{kotlin/com/bibleverse/daily/{ui/{screen,component,viewmodel,theme,navigation},data/{model,database,converter,repository},widget,work,notification,di},res/{drawable,layout,values,xml}}

# Stage and push
git add .
git commit -m "Initial commit: Bible Verse Daily app structure"
git push -u origin main
