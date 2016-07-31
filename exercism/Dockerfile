 FROM alpine:latest
  
RUN apk --no-cache add wget ca-certificates \ 
    && wget "http://github.com/exercism/cli/releases/download/v2.2.6/exercism-linux-64bit.tgz" -O "exercism-linux-64bit.tgz" \
    && tar -xzvf exercism-linux-64bit.tgz \
    && mv exercism /usr/bin/ \
    && exercism configure --dir=/work/exercism
                                                                                                                                                                         
 

