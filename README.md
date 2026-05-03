# Prerequisites
These instructions help you install Python 3 and required tools for running projects.
Copy code snippets and run from the command-line.

## Mac Setup (Homebrew)

1. Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Install Git
```
$ brew install git
```

3. Install Python
```
brew install python
```

4. Create a Virtual Environment
```
python3 -m venv .venv
```

5. Active Virtual Environment
```
source .venv/bin/activate
```


## Step 0. Install Homebrew (Mac only)
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### Step 1. Install Git
- Mac: `$ brew install git`
- Windows: `winget install --id Git.Git -e --source winget`

### Step 2. Install the latest version of Python
- Mac:
  - Update Brew: `brew update`
  - Install: `brew install python`
- Windows: `winget install Python.Python.3`
