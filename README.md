# Flutter로 제작한 NomardCoders에서 제공하는 API를 활용한<br/> 오늘의 Naver Webtoon을 표시해주는 Toonflix App입니다.

## Screen

Screen은 Home, Detail 총 2개의 Screen으로 이루어져있습니다.

- Home Screen

  Home Screen은 가로로 Scroll이 되며 오늘의 웹툰을 Thumbnail & Title로 표시해줍니다.<br/>
  추가로 확인하고 싶은 Webtoon Thumbnail을 Tap 시 Detail Screen으로 이동을 하게됩니다.<br/>
  (비디오)

- Detail Screen

  Detail Screen은 세로로 Scroll이 되며 Thumbnail, Title, About, Genre, Age, Episode로 구성되어있습니다.<br/>
  추가로 Appbar에 Favorite 기능을 추가하여 우측 상단에 Heart Icon을 Tap 시 Favorite 설정/해제가 가능합니다.<br/>
  Favorite 기능의 경우 "shared_preferences" plugin을 사용하여 Local Storage에 저장되어있어 App이 Reload 될 때 이전 정보를 가져오게 구현하였습니다.<br/>
  Episode Button을 Tap 시 "url_launcher" plugin을 사용하여 해당화 Naver Webtoon으로 이동하는 기능도 구현하였습니다.<br/>
  (비디오)
