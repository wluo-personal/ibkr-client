###########
# BUILDER #
###########
FROM openjdk:11
ARG wdir='/usr/src/'
ARG appfolder='clientportal.gw'
ARG fullpath=${wdir}${appfolder}
COPY ${appfolder} ${fullpath}
WORKDIR ${fullpath}
RUN chmod 700 bin/run.sh
#root/conf.yam
#ENTRYPOINT ["/bin/bash"]
ENTRYPOINT ["bin/run.sh", "root/conf.yam"]
