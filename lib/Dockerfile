FROM quay.io/excelottah6/izuku-md
RUN git clone https://github.com/Godsoulsolos/RENGOKU-MD /root/Godsoulsolos
WORKDIR /root/Godsoulsolos/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
