FROM quay.io/excelottah6/izuku-md
RUN git clone https://github.com/Godsoulsolos/RENGOKU-MD /root/RENGOKU-MD
WORKDIR /root/RENGOKU-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
