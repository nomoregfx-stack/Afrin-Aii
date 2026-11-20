# Afrin AI — Personal Assistant (Starter)

এটি Afrin AI-এর প্রথম Android starter project।

## প্রথম সংস্করণের সুবিধা
- বাংলা/ইংরেজি speech input (ফোনের speech recognition service-এর ওপর নির্ভরশীল)
- Android Text-to-Speech reply
- YouTube, Facebook, TikTok ও Chrome চালু করার উদাহরণ
- Contacts থেকে নাম খুঁজে Android Dialer খোলা (কল নিজে থেকে করা হয় না)
- Alarm app খোলা
- সময় বলা

## Build
GitHub-এ repository-তে project-এর সব ফাইল upload করুন। এরপর Actions → Build Afrin AI APK → Run workflow। সফল হলে `Afrin-AI-debug-apk` artifact download করে ZIP extract করুন।

## সীমাবদ্ধতা
- এটি এখনো পূর্ণ AI chatbot নয়; cloud/local LLM সংযুক্ত করা হয়নি।
- “Hey Afrin” always-listening wake word এখনো নেই।
- Speech recognition offline হবে কি না তা ফোনের ভাষা ও downloaded speech pack-এর ওপর নির্ভর করে।
- Reminder বর্তমানে শুধু নির্দেশনা দেয়; স্থায়ী reminder storage পরের সংস্করণে যোগ করতে হবে।
- Android permission চাইলে প্রয়োজন অনুযায়ী Allow দিন।
