# IoT_firmscanner

# binwalk
https://github.com/ReFirmLabs/binwalk?tab=readme-ov-file
# 一番安全
docker build --build-arg SCRIPT_DIRECTORY="$($PWD.Path)" -t binwalkv3 .
# もしくは Get-Location
docker build --build-arg SCRIPT_DIRECTORY="$(Get-Location)" -t binwalkv3 .



# SBOM生成ツールSyft
https://github.com/anchore/syft
# 使い方
https://qiita.com/matsumokei/items/21a797029568594cb223


# 脆弱性スキャンツールGrype
https://github.com/anchore/grype
# 使い方
https://qiita.com/matsumokei/items/d4b0b595eabc4384dde1


# 
https://speakerdeck.com/owaspkansai/owaspkansai-fstm-230422?slide=7
https://coky-t.gitbook.io/owasp-fstm-ja
https://github.com/scriptingxss/owasp-fstm
