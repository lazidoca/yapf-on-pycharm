# yapf-on-pycharm

Yapf is a formatter for Python files developed by Google. It can help you automatiaccally format the code.

## Install yapf package

Open your terminal / cmd run the following command:

```
pip install yapf
```

## Open Pycharm/Intellij

1.  Open external tool: `Preference → Tools → External Tools → +`
    ![External tool](imgs/Image-1.png?raw=true)

2.  Configuration
    <ul>
     <li>Name：Yapf (Whatever name)</li>
     <li>Tools settings:</li>

```
Programs：yapf （Make sure you have installed）
Parameters: -i $FilePath$
Working directory: $ProjectFileDir$
```

```
Output filters: $FILE_PATH$\:$LINE$\:$COLUMN$\:.*
```

![External tool setting1](imgs/Image-2.png?raw=true)

## Set keyboard shortcut

1. Open External Tools keymap: `Preference → Keymap → External Tools → External Tools -> Yapf`
   ![External tool key map](imgs/Image-3.png?raw=true)`
2. Add Keyboard shortcut
   ![Add keyboard shortcut](imgs/Image-4.png?raw=true)
   ![Set keyboard shortcut](imgs/Image-5.png?raw=true)

## Usage

- From menu:

  `External Tools → Yapf`

- Keyboard shortcut

  `Alt + F`
