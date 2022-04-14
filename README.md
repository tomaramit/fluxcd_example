flux bootstrap git \
 --url=ssh://cloud_user_p_2aa7f45a@linuxacademygclabs.com@source.developers.google.com:2022/p/playground-s-11-e0f4edef/r/testrepoe0f4edef \
 --private-key-file=/Users/felipe/.ssh/id_rsa \
 --silent \
 --path=./clusters/myCluster \
 --branch="master"

flux get kustomization -A

flux get source git -A

flux get hr -A
