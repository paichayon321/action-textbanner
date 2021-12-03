# action-textbanner

```
  Run_Text_Banner:
    runs-on: ubuntu-latest
    steps:
      - name: Step 1 -Call Action TextBanner 
        uses: paichayon321/action-textbanner@main
        with:
          banner_text: 'Hello Toom'
 
      - name: Step 2 - Show Text Banner Result
        run: cat ./banner.txt
```
