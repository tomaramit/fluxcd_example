flux bootstrap git \
 --url=ssh://cloud_user_p_c5a5eba2@linuxacademygclabs.com@source.developers.google.com:2022/p/playground-s-11-990e5240/r/testrepo \
 --private-key-file=/Users/felipe/.ssh/id_rsa \
 --silent \
 --path=./clusters/wordpress_cluster \
 --branch="master"

git clone ssh://cloud_user_p_c5a5eba2@linuxacademygclabs.com@source.developers.google.com:2022/p/playground-s-11-990e5240/r/testrepo

flux get kustomization -A

flux get source git -A

flux get hr -A

.
├── \_config.yml
├── apps
│ ├── begin-with-the-crazy-ideas.textile
│ └── on-simplicity-in-technology.markdown
├── \_includes
