git config --gloabl http.sslVerify false
required for make step in "quickstart" on K3s to avoid
"fatal: unable to access 'https://gopkg.in/yaml.v2/': server certificate verification failed. CAfile: none CRLfile: none"
