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

## Windows Setup (Winget)

1. Install Git
```
winget install --id Git.Git -e
```

2. Install Python
```
winget install Python.Python.3
```

3. Create a Virtual Environment
```
python3 -m venv .venv
```

4. Activate the Virtual Environment
```
.venv\Scripts\activate
```
