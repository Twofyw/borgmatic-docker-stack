FROM monachus/borgmatic

VOLUME /data
VOLUME /borgmatic

#CMD ["-c", "/borgmatic/config/config.yaml", "--verbosity", "1"]
CMD /usr/local/bin/borgmatic -c /borgmatic/config/config.yaml --verbosity 1 >> /borgmatic/log 2>&1
