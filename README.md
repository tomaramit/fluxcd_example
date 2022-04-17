flux bootstrap git \
 --url=ssh://cloud_user_p_7fb194e5@linuxacademygclabs.com@source.developers.google.com:2022/p/playground-s-11-d1c82b83/r/playground1c82b83 \
 --private-key-file=/Users/felipe/.ssh/id_rsa \
 --silent \
 --path=./clusters/wordpress_cluster \
 --branch="master"

flux get kustomization -A

flux get source git -A

flux get hr -A

.
├── \_config.yml
├── apps
│ ├── begin-with-the-crazy-ideas.textile
│ └── on-simplicity-in-technology.markdown
├── \_includes
