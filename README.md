# AnalysisProjectDependencies

中文README：[README_CN](https://github.com/Kyson/AnalysisProjectDependencies/blob/master/README_CN.md)

This project is applied to the analysis project of Java, Android, etc,will support other languages and other subsequent analyses function in the future,u only need to configure the project module,then it can display the project's dependency network diagram.

![project_analysis_showcase](https://raw.githubusercontent.com/Kyson/AnalysisProjectDependencies/master/ART/project_analysis_showcase.gif)

for more detail, go to youtube:

[![project_analysis_showcase](https://img.youtube.com/vi/v9Xzxle-9v0/0.jpg)](https://www.youtube.com/watch?v=v9Xzxle-9v0)

## QuickStart

### 0x00

- install python 2.7.x  and install bower.
- `cd AnalysisProjectDependencies`.
- run `bower install`

### 0x01

- Configure the module in the `analysis_dependencies.conf` file,under section `java_modules`,format: name = module path,name must be unique.

### 0x02

if macOS or linux,just run `source generate_and_host.sh`
for other os,follow these steps:

- run `python entrance_generate.py`,it will generate json file in output dir.
- run `python -m SimpleHTTPServer 8080`.
- open `http://localhost:8080/` in browser.

## Features

- Analysis Dependencies
- and so on...



