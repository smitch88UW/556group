# 556group

Some code Brian suggested for loading data:

if (!file.exists("filename.csv")) {
download.file("url", "filename.csv")
}

read.csv("filename.csv")