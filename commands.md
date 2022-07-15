npm run devServer -- --host localhost --port 8440 --knownHost localhost --knownPort 8440
npm run devClient -- crawl --host localhost --port 8440 --webPort 1337
npm run devWeb -- --host localhost --port 8440 --webPort 1337

npm run devServer -- --host localhost --port 8441 --knownHost localhost --knownPort 8440
npm run devServer -- --host localhost --port 8444 --knownHost localhost --knownPort 8440
npm run devServer -- --host localhost --port 8446 --knownHost localhost --knownPort 8440
npm run devServer -- --host localhost --port 8448 --knownHost localhost --knownPort 8440
npm run devServer -- --host localhost --port 8450 --knownHost localhost --knownPort 8440

<!-- Alvaro: npm run devClient worked for me, but it does not ends so I can't run the following command -->

node client insert --host localhost --port 8440 --id 2
node client insert --host localhost --port 8440 --id 5 --displayName "Alvaro is cool" --reputation 99 --aboutMe "I'm so cool I need no description"
node client lookup --host localhost --port 8440 --id 2
node client remove --host localhost --port 8440 --id 2
npm run client -- insert --host localhost --port 8440 --id 2
npm run client -- insert --host localhost --port 8440 --id 5 --displayName "Alvaro is cool" --reputation 99 --aboutMe "I'm so cool I need no description"
npm run client -- lookup --host localhost --port 8440 --id 2
npm run client -- remove --host localhost --port 8440 --id 2