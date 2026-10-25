# Publish (needs Mark's yes: a new public repo under his account)

```
cd /Users/markksantos/Developer/automation/seo-loop/moves-100/datasets/video-caption-reading-speed
gh repo create markksantos/video-caption-reading-speed --public --source . --description "Caption Reading Speed Study: 387 Videos Measured (CC BY 4.0) - https://www.markstudios.com/research/caption-reading-speed-study" --homepage "https://www.markstudios.com/research/caption-reading-speed-study" --push
gh repo edit markksantos/video-caption-reading-speed --add-topic dataset --add-topic open-data
```

After it's live: add the repo URL to the page's Dataset `sameAs`/`distribution` and to llms.txt, and submit the page to Google Dataset Search via the existing Dataset schema.
