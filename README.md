# Tapestry 5 demonstration application - Hotel Booking

Steps to use the application:
1. build using maven: mvn clean install
2. If you want to run selenium test cases, remove the <skipTests> tag from master pom.xml
3. the deploy-able will be a war file
4. Register as a new user
5. On search page, enter "Hotel" as search parameter



narma13@NARMA13 MINGW64 /c/MANJU/Project
$ cd HotelBookingApp/

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp
$ git init
Initialized empty Git repository in C:/MANJU/Project/HotelBookingApp/.git/

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git remote add origin "https://github.com/manju2606/HotelBookingSampleApp.git"

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git pull origin master
remote: Counting objects: 122, done.
remote: Compressing objects: 100% (101/101), done.
remote: Total 122 (delta 8), reused 122 (delta 8), pack-reused 0
Receiving objects: 100% (122/122), 100.41 KiB | 0 bytes/s, done.
Resolving deltas: 100% (8/8), done.
From https://github.com/manju2606/HotelBookingSampleApp
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master



narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git add .

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git commit .
Aborting commit due to empty commit message.

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git commit -m "Edit the Readme.md"
[master add3acc] Edit the Readme.md
 1 file changed, 27 insertions(+), 1 deletion(-)

narma13@NARMA13 MINGW64 /c/MANJU/Project/HotelBookingApp (master)
$ git push -u origin master
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 817 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local objects.
To https://github.com/manju2606/HotelBookingSampleApp.git
   6e13986..add3acc  master -> master
Branch master set up to track remote branch master from origin.

$
