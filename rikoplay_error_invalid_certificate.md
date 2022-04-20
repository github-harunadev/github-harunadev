한국어로도 서술되어있습니다. 아래로 조금만 더 스크롤하시면 있어요.


# rikoplayIdentifier Error (Invalid URL error)

There're many ways to analyze the problem:

- World creator has installed the corrupt Token URL to the system
- The server is not responding (server falut)
- The server is not responding (client fault)
- The server certificate is not installed on the PC

## World creator has installed the corrupted Token URL to the system

IF no one is moving from the spawn point, you can guess out that there's a wrong Token URL in the server.
To fix this problem, **you'll have to encourage the world creator to install a correct Token URL to the system, and reupload.**

There's nothing much you (as a client) can do to fix the problem).

## The server is not responding (server fault)

rikoplayIdentifier's challenge service runs on a very small and weak server. The mighty, Samsung Galaxy S9 (yeah, the smartphpone!), is running Ubuntu 18.04.
**Try to open https://haruna.dev/ping on your favorite web browser. If you get a prompt of "pong", there're no critical problem in the server.
If there's a connection error, it might be the server fault.**

## The server is not responding (client fault)

Sometimes, internet provider may block the domain, making not able to connect through anything inside the server.
Especially, The Great Firewall in China (haha), may block you to make a connection.
If other player is moving, but you're having an Invalid URL error, and server connection is blocked, then you can guess out that the connection from your client to my web server is getting somehow blocked.

**Try getting a working VPN that has a server on other countries (Especially South Korea would be great to try).**

## The server certificate is not installed on your PC

If any of the solution above does not fix the error, you may have to guess that this is the main reason.
(and you will have to, because some of my closed beta testers encountered this error)
This error occurs when there's no Let's Encrypt certificate found in the PC, making not able to get any result from the web server. 
This is a fault of Windows, not providing any client certificates of Let's Encrypt to your PC. (haha microsoft)

**This error is not critical, but this situation is critical because your PC is missing some of the necessary client certificates.**

In order to solve this problem, **please follow the link below from VRChat to install Let's Encrypt client certificate in your PC.**

https://help.vrchat.com/hc/en-us/articles/4408619131795-Video-Players-failing-with-CERTIFICATE-VERIFY-FAILED-in-output-logs

# rikoplayIdentifier 에러 (Invalid URL 오류)

어떠한 이유가 문제를 발생하는지 먼저 일아볼 필요가 있습니다:

- 월드 제작자가 질못된 Token URL을 월드에 설치함
- 서버가 응답하지 않음 (서버 탓)
- 서버가 응답하지 않음 (클라이언트 탓)
- 컴퓨터에 인증서가 설치되어있지 않음

## 월드 제작자가 질못된 Token URL을 월드에 설치함

만약 월드에 있는 어느 플레이어도 움직이지 않는다면, 월드 제작자가 잘못된 토큰 URL을 월드에 설치했을 가능성이 높습니다.
이 문제를 해결하려면 **월드 제작자에게 정확한 토큰 URL을 월드에 설치한 수 재업로드해야한다고 월드 제작자에게 알려주어야합니다.**

클라이언트로써 이 문제를 효과적으로 해결할 수 있는 방법은 없습니다.

## 서버가 응답하지 않음 (서버 탓)

rikoplayIdentifier의 챌린지 서비스는 삼성 갤럭시 S9 스마트폰 (Ubuntu 18.04) 에서 작동됩니다.
**https://haruna.dev/ping 이 링크를 브라우저에서 열어보세요. 만약 "pong" 이라는 응답이 뜬다면, 서버와 연결이 문제가 없는것입니다.
만약 연결 문제가 발생한다면, 서버가 다운되었을 가능성이 큽니다.**

## 서버가 응답하지 않음 (클라이언트 탓)

인터넷 서비스 제공자 또는 공유기가 연결을 막을 수도 있습니다.
예를 들어, 중국의 황금방패 (The Great Firewall of China로 불리기도 하죠 ㄹㅇㅋㅋ)가 서버의 연결을 끊을 수 있습니다.
만약 다른 플레이어는 움직이는데, 본인은 Invalid URL 에러가 뜨면서 동시에 브라우저에서 "pong" 응답이 뜨지 않는다면 이러한 이유때문에 문제가 발생하는것으로 볼 수 있습니다.

**한국에 서버를 둔 VPN 서비스를 이용해보세요.**

## 컴퓨터에 인증서가 설치되어있지 않음

어떠한 해결 방법도 문제를 해결하지 못했다면, 이 이유가 최종 이유일것입니다.
(클로즈 베타 테스터분들중 몆몆분들이 이 문제를 겪었으니 그럴 수 있습니다)
Let's Encrypt에서 제공하는 클라이언트 인증서가 컴퓨터에 설치되어있지 않아 생기는 문제입니다.
윈도우가 이 인증서를 기본으로 포함하지 않았거나 업데이트에 포함하지 않아서 생기기도 합니다.

**이 에러는 중요하지 않지만 이 문제 자체는 중요합니다. 컴퓨터에 설치되어있어야할 중요 인증서중 몆몆이 빠졌기 때문이죠.**

이 문제를 해결하기 위해, **아래 링크에서 Let's Encrypt에서 제공하는 인증서를 설치하고, 컴퓨터를 다시 시작하세요.**

https://help.vrchat.com/hc/en-us/articles/4408619131795-Video-Players-failing-with-CERTIFICATE-VERIFY-FAILED-in-output-logs
