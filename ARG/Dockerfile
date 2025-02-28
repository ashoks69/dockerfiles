ARG version
FROM almalinux:${version:-9}
ENV name="ashok" \
    org="vam" \
    id="120H101080RS"
#here user1 is key, someuser is default value
ARG USERNAME=ashok
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]