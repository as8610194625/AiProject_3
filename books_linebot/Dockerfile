FROM python:3

WORKDIR /line-bot
COPY ./Project-linebot /line-bot
RUN pip3 install requests
RUN pip3 install bs4
RUN pip3 install Flask
RUN pip3 install line-bot-sdk
RUN pip3 install pymongo
RUN pip3 install elasticsearch
RUN pip3 install 'pymongo[srv]'
RUN pip3 install elasticsearch async