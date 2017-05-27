# vscode-react-native-snippets
The snippets of react native (virtual studio code)

## Setup

1. **Copy Snippets File**

copy javascriptreact.json to to the following directory:
/Users/xxxxxx/Library/Application Support/Code/User/snippets

2. **Edit Snippets**

Code -> Preferences -> User Snippets -> JavaScript

## Usage
Place your snippets for Javascript here. Each snippet is defined under a snippet name and has a prefix, body and description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:$1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the same ids are connected.

## Example:
```
	"Print to console": {
		"prefix": "log",
		"body": [
			"console.log('$1');",
			"$2"
		],
		"description": "Log output to console"
	}
```

## preview

### constructor
```
    "constructor": {
        "prefix": "cst",
        "body": [
            "constructor(props: Object) {",
            "    super(props)",
            "",
            "    $1",
            "}"
        ]
    },
```

### Navigation Options
```
    "navigation ": {
        "prefix": "navopt",
        "body": [
            "static navigationOptions = ({ navigation }) => ({",
            "    title: '${1:title}',",
            "})"
        ]
    },
```

### 还有很多，不写了，自己下载看