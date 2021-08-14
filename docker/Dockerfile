FROM node:lts-alpine3.12

LABEL AUTHOR="none" \
      VERSION=0.1.4

ARG KEY="-----BEGIN OPENSSH PRIVATE KEY-----\n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\n-----END OPENSSH PRIVATE KEY-----"

ENV DEFAULT_LIST_FILE=crontab_list.sh \
    CUSTOM_LIST_MERGE_TYPE=append \
    COOKIES_LIST=/scripts/logs/cookies.list \
    REPO_URL=git@github.com:underlaw/jd_scripts.git \
    REPO_BRANCH=master

RUN set -ex \
    && apk update \
    && apk upgrade \
    && apk add --no-cache bash tzdata git moreutils curl jq openssh-client python3 py3-pip \
    && rm -rf /var/cache/apk/* \
    && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone \
    && mkdir -p /root/.ssh \
    && echo -e $KEY > /root/.ssh/id_rsa \
    && chmod 600 /root/.ssh/id_rsa \
    && ssh-keyscan github.com > /root/.ssh/known_hosts \
    && git clone -b $REPO_BRANCH $REPO_URL /scripts \
    && cd /scripts \
    && mkdir logs \
    && python3 -m pip install requests \
    && npm config set registry https://registry.npmjs.org \
    && npm install \
    && cp /scripts/docker/docker_entrypoint.sh /usr/local/bin \
    && chmod +x /usr/local/bin/docker_entrypoint.sh

WORKDIR /scripts

ENTRYPOINT ["docker_entrypoint.sh"]

CMD [ "crond" ]