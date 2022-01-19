# DeepL
DeepL Free API

## Fetures
- Free, no account registration required
- Custom DeepL AuthKey
- Custom Source Language
- Custom Target Language

## Usage 
~~~
  --help, -h show this help message and exit
  --text -t text to translate, required
  --auth_key -a authKey, optional
  --source_lang -s source language, default: Auto, optional
  --target_lang -l target language, Default: ZH, optional
~~~

### Common
`python3 deepl.py -t stepwells`

### Custom
`python3 deepl.py -t stepwells -s EN -l ZH`

### Return
~~~json
{
  "translations": [
    {
      "detected_source_language": "EN", 
      "text": "阶梯水井"
    }
  ], 
  "usage": 193, 
  "author": "https://github.com/missuo"
}
~~~

## **language supported:**

- `DE`: 德语
- `EN`: 英语
- `ES`: 西班牙语
- `FR`: 法语
- `IT`: 意大利语
- `JA`: 日语
- `NL`: 荷兰语
- `PL`: 波兰语
- `PT`: 葡萄牙语
- `RU`: 俄语
- `ZH`: 中文
- `BG`: 保加利亚语
- `CS`: 捷克语
- `DA`: 丹麦语
- `EL`: 希腊语
- `ET`: 爱沙尼亚语
- `FI`: 芬兰语
- `HU`: 匈牙利语
- `LT`: 立陶宛语
- `LV`: 拉脱维亚语
- `RO`: 罗马尼亚语
- `SK`: 斯洛伐克语
- `SL`: 斯洛文尼亚语
- `SV`: 瑞典语

## TO DO
 - Provide open API interface
 - Document translation

## License 
MIT License
