Sturtup

'''
docker run -it --platform linux/amd64 \      
 --name hummingbot \
 -v /Users/User/hummingbot/logs:/logs \
 -v /Users/User/hummingbot/conf:/conf \
 -v /Users/User/hummingbot/hummingbot/connector/exchange/peatio:/home/hummingbot/hummingbot/connector/exchange/peatio \
 hummingbot/hummingbot:version-1.13.0

'''