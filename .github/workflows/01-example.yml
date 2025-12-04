name: HelloWorld
# When to trigger this pipeline. We can trigger on push or manual or someother events like creating PR, updating PR, creating branches, creating issues
on: [push] # triggers
jobs: # Pipeline. One workflow can have multiple pipelines
  hello:
    runs-on: ubuntu-latest # Linux OS. We can have windows or MAC
    steps: # stages
      - name: step1
        run: echo "Hello World"
      - name: step2
        run: echo "Hello GitHub Actions"