FROM browserless/chrome
WORKDIR /usr/src/app
ADD ./index.js index.js
ADD ./launch.sh launch.sh
EXPOSE 80
CMD ["./launch.sh"]