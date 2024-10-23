<!-- ⭐ Dean Tumabcao's README Template v89 -->
<a id='readme-top'></a>

<!-- LOGO AND NAME -->
<div align='center'>
  
  <!-- Logo <img src='/logo.svg' width=15/60% alt='Project Name'> -->
  <img src='/ReadMeTemplateBanner.svg' alt='Project Artwork'> <!-- Banner inkscape twitter header template -->

  <!-- Project Name -->
  # README Template

  <!-- Tags -->
  <a href='#---'><img alt='Game tag' height='20' src='https://img.shields.io/badge/GAME-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xNC45OTggNWE3IDcgMCAwIDEgLjI0IDEzLjk5NmwtLjI0LjAwNEg5LjAwMmE3IDcgMCAwIDEtLjI0LTEzLjk5Nkw5LjAwMSA1em0wIDEuNUg5LjAwMmE1LjUgNS41IDAgMCAwLS4yMjEgMTAuOTk2bC4yMjEuMDA0aDUuOTk2YTUuNSA1LjUgMCAwIDAgLjIyMS0xMC45OTZ6TTggOWEuNzUuNzUgMCAwIDEgLjc1Ljc1djEuNDk4aDEuNWEuNzUuNzUgMCAwIDEgMCAxLjVoLTEuNXYxLjUwMmEuNzUuNzUgMCAwIDEtMS41IDB2LTEuNTAyaC0xLjVhLjc1Ljc1IDAgMSAxIDAtMS41aDEuNVY5Ljc1QS43NS43NSAwIDAgMSA4IDltNi43NSAzLjVhMS4yNSAxLjI1IDAgMSAxIDAgMi41YTEuMjUgMS4yNSAwIDAgMSAwLTIuNW0yLTMuNWExLjI1IDEuMjUgMCAxIDEgMCAyLjVhMS4yNSAxLjI1IDAgMCAxIDAtMi41Ii8+PC9zdmc+'></a>
  <a href='#---'><img alt='App tag' height='20' src='https://img.shields.io/badge/APP-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Im0xOC40OTIgMi4zM2wzLjE3OSAzLjE4YTIuMjUgMi4yNSAwIDAgMSAwIDMuMTgybC0yLjU4NCAyLjU4NEEyLjI1IDIuMjUgMCAwIDEgMjEgMTMuNXY1LjI1QTIuMjUgMi4yNSAwIDAgMSAxOC43NSAyMUg1LjI1QTIuMjUgMi4yNSAwIDAgMSAzIDE4Ljc1VjUuMjVBMi4yNSAyLjI1IDAgMCAxIDUuMjUgM2g1LjI1YTIuMjUgMi4yNSAwIDAgMSAyLjIyNSAxLjkxNUwxNS4zMSAyLjMzYTIuMjUgMi4yNSAwIDAgMSAzLjE4MiAwTTQuNSAxOC43NWMwIC40MTUuMzM2Ljc1Ljc1Ljc1aDUuOTk5bC4wMDEtNi43NUg0LjV6bTguMjQ5Ljc1aDYuMDAxYS43NS43NSAwIDAgMCAuNzUtLjc1VjEzLjVhLjc1Ljc1IDAgMCAwLS43NS0uNzVoLTYuMDAxek0xMC41IDQuNUg1LjI1YS43NS43NSAwIDAgMC0uNzUuNzV2Nmg2Ljc1di02YS43NS43NSAwIDAgMC0uNzUtLjc1bTIuMjUgNC44MXYxLjk0aDEuOTR6bTMuNjItNS45MThMMTMuMTkzIDYuNTdhLjc1Ljc1IDAgMCAwIDAgMS4wNjFsMy4xNzkgMy4xNzlhLjc1Ljc1IDAgMCAwIDEuMDYgMGwzLjE4LTMuMTc5YS43NS43NSAwIDAgMCAwLTEuMDZsLTMuMTgtMy4xOGEuNzUuNzUgMCAwIDAtMS4wNiAwIi8+PC9zdmc+'></a>
  <a href='#---'><img alt='Library tag' height='20' src='https://img.shields.io/badge/LIBRARY-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik00IDNoMWMxLjA1NCAwIDEuOTE4LjgxNiAxLjk5NSAxLjg1TDcgNXYxNGEyIDIgMCAwIDEtMS44NSAxLjk5NEw1IDIxSDRhMiAyIDAgMCAxLTEuOTk1LTEuODVMMiAxOVY1YzAtMS4wNTQuODE2LTEuOTE4IDEuODUtMS45OTV6aDF6bTYgMGgxYzEuMDU0IDAgMS45MTguODE2IDEuOTk1IDEuODVMMTMgNXYxNGEyIDIgMCAwIDEtMS44NSAxLjk5NEwxMSAyMWgtMWEyIDIgMCAwIDEtMS45OTUtMS44NUw4IDE5VjVjMC0xLjA1NC44MTYtMS45MTggMS44NS0xLjk5NXpoMXptNi45NzQgMmMuODQgMCAxLjYwOC41MzEgMS44OSAxLjM0NmwuMDQ3LjE1N2wzLjAxNSAxMS43NDZhMiAyIDAgMCAxLTEuMjk2IDIuMzkxbC0uMTQ0LjA0M2wtLjk2OS4yNDhhMiAyIDAgMCAxLTIuMzg3LTEuMjg0bC0uMDQ3LS4xNTVsLTMuMDE2LTExLjc0NWEyIDIgMCAwIDEgMS4yOTgtMi4zOTJsLjE0My0uMDQzbC45NjgtLjI0OHEuMjUtLjA2NC40OTgtLjA2NE01IDQuNUg0YS41LjUgMCAwIDAtLjQ5Mi40MUwzLjUgNXYxNGMwIC4yNDQuMTc3LjQ1LjQxLjQ5Mkw0IDE5LjVoMWMuMjQ1IDAgLjQ1LS4xNzguNDkyLS40MUw1LjUgMTlWNWEuNS41IDAgMCAwLS40MS0uNDkyem02IDBoLTFhLjUuNSAwIDAgMC0uNDkyLjQxTDkuNSA1djE0YzAgLjI0NC4xNzcuNDUuNDEuNDkybC4wOS4wMDhoMWMuMjQ1IDAgLjQ1LS4xNzguNDkyLS40MUwxMS41IDE5VjVhLjUuNSAwIDAgMC0uNDEtLjQ5MnptNS45NzUgMmwtLjA2My4wMDRsLS4wNjMuMDEzbC0uOTY4LjI0N2EuNS41IDAgMCAwLS4zNzYuNTFsLjAxNS4xbDMuMDE2IDExLjc0NWEuNS41IDAgMCAwIC40ODMuMzc1bC4wNjMtLjAwM2wuMDYyLS4wMTJsLjk3LS4yNWEuNS41IDAgMCAwIC4zNzQtLjUxOWwtLjAxNS0uMDg4bC0zLjAxNS0xMS43NDdhLjUuNSAwIDAgMC0uNDgzLS4zNzUiLz48L3N2Zz4='></a>
  <a href='#---'><img alt='Documentation tag' height='20' src='https://img.shields.io/badge/DOCUMENTATION-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik02IDJhMiAyIDAgMCAwLTIgMnYxNmEyIDIgMCAwIDAgMiAyaDEyYTIgMiAwIDAgMCAyLTJWOS44MjhhMiAyIDAgMCAwLS41ODYtMS40MTRsLTUuODI4LTUuODI4QTIgMiAwIDAgMCAxMi4xNzIgMnptLS41IDJhLjUuNSAwIDAgMSAuNS0uNWg2VjhhMiAyIDAgMCAwIDIgMmg0LjV2MTBhLjUuNSAwIDAgMS0uNS41SDZhLjUuNSAwIDAgMS0uNS0uNXptMTEuODggNC41SDE0YS41LjUgMCAwIDEtLjUtLjVWNC42MnoiLz48L3N2Zz4='></a>
  <a href='#---'><img alt='Template tag' height='20' src='https://img.shields.io/badge/TEMPLATE-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik02LjI1IDNBMy4yNSAzLjI1IDAgMCAwIDMgNi4yNXYxMS41QTMuMjUgMy4yNSAwIDAgMCA2LjI1IDIxaDExLjVBMy4yNSAzLjI1IDAgMCAwIDIxIDE3Ljc1VjYuMjVBMy4yNSAzLjI1IDAgMCAwIDE3Ljc1IDN6TTQuNSA2LjI1YzAtLjk2Ni43ODQtMS43NSAxLjc1LTEuNzVoNVY3aC0xLjVBMi43NSAyLjc1IDAgMCAwIDcgOS43NXYxLjVINC41em0yLjUgNi41djEuNUEyLjc1IDIuNzUgMCAwIDAgOS43NSAxN2gxLjV2Mi41aC01YTEuNzUgMS43NSAwIDAgMS0xLjc1LTEuNzV2LTV6bTQuMjUgMi43NWgtMS41Yy0uNjkgMC0xLjI1LS41Ni0xLjI1LTEuMjV2LTEuNWgyLjc1em0xLjUgMS41aDEuNUEyLjc1IDIuNzUgMCAwIDAgMTcgMTQuMjV2LTEuNWgyLjV2NWExLjc1IDEuNzUgMCAwIDEtMS43NSAxLjc1aC01em0yLjc1LTQuMjV2MS41YzAgLjY5LS41NiAxLjI1LTEuMjUgMS4yNWgtMS41di0yLjc1em0xLjUtMS41di0xLjVBMi43NSAyLjc1IDAgMCAwIDE0LjI1IDdoLTEuNVY0LjVoNWMuOTY2IDAgMS43NS43ODQgMS43NSAxLjc1djV6TTEyLjc1IDguNWgxLjVjLjY5IDAgMS4yNS41NiAxLjI1IDEuMjV2MS41aC0yLjc1em0tMS41IDB2Mi43NUg4LjV2LTEuNWMwLS42OS41Ni0xLjI1IDEuMjUtMS4yNXoiLz48L3N2Zz4='></a>
  <a href='#---'><img alt='Test tag' height='20' src='https://img.shields.io/badge/TEST-7F7F7F?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik04IDQuNWgxdjYuMjM4YzAgLjM3NS0uMDk0Ljc0NC0uMjczIDEuMDc0bC0zLjU4NCA2LjYwM0ExLjc1IDEuNzUgMCAwIDAgNi42OCAyMWgxMC42MzhhMS43NSAxLjc1IDAgMCAwIDEuNTM4LTIuNTg1bC0zLjU4NC02LjYwM0EyLjI1IDIuMjUgMCAwIDEgMTUgMTAuNzM4VjQuNWgxQS43NS43NSAwIDAgMCAxNiAzSDhhLjc1Ljc1IDAgMCAwIDAgMS41bTIuNSA2LjIzOFY0LjVoM3Y2LjIzOGMwIC42MjUuMTU2IDEuMjQuNDU0IDEuNzlsLjggMS40NzJIOS4yNDZsLjgtMS40NzNhMy43NSAzLjc1IDAgMCAwIC40NTQtMS43ODlNOC40MzIgMTUuNWg3LjEzNmwxLjk3MSAzLjYzYS4yNS4yNSAwIDAgMS0uMjIuMzdINi42ODFhLjI1LjI1IDAgMCAxLS4yMi0uMzd6Ii8+PC9zdmc+'></a>
  
</div>



<!-- QUICK INFO -->
<div align='center'>

  <!-- Brief description and hook -->
  Impress prospective customers with this README tailored to grab their attention and provide vital information.  
  All media in this document is intended for example purposes only.

  <!-- Platforms -->
  ## 💻 Platforms
  <a href='https://www.microsoft.com/windows/'><img alt='Windows' height='30' src='https://img.shields.io/badge/Windows-0078D6?style=&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yLjc1IDcuMTg5VjIuODY1YzAtLjEwMiAwLS4xMTUuMTE1LS4xMTVoOC42MjJjLjEyOCAwIC4xNCAwIC4xNC4xMjhWMTEuNWMwIC4xMjggMCAuMTI4LS4xNC4xMjhIMi44NjVjLS4xMDIgMC0uMTE1IDAtLjExNS0uMTE2ek03LjE4OSAyMS4yNUgyLjg2NWMtLjEwMiAwLS4xMTUgMC0uMTE1LS4xMTZWMTIuNTljMC0uMTI4IDAtLjEyOC4xMjgtLjEyOGg4LjYzNWMuMTAyIDAgLjExNSAwIC4xMTUuMTE1djguNTdjMCAuMDkgMCAuMTAzLS4xMTYuMTAzek0yMS4yNSA3LjE4OXY0LjMxYzAgLjExNiAwIC4xMTYtLjExNi4xMTZoLTguNTU3Yy0uMTAyIDAtLjEyOCAwLS4xMjgtLjExNVYyLjg2NWMwLS4wOSAwLS4xMDIuMTE1LS4xMDJoOC40OGMuMjA2IDAgLjIwNiAwIC4yMDYuMjA1em0tOC43NjMgOS42NjF2LTQuMjczYzAtLjA5IDAtLjExNS4xMDMtLjA5aDguNjIxYy4wMjYgMCAwIC4wOSAwIC4xNDJ2OC41MThhLjA2LjA2IDAgMCAxLS4wMTcuMDZhLjA2LjA2IDAgMCAxLS4wNi4wMTdIMTIuNTRzLS4wOSAwLS4wNzctLjA5VjE2Ljg1eiIvPjwvc3ZnPg==&logoColor=white'></a>
  <a href='https://www.apple.com/macos/sonoma/'><img alt='macOS' height='30' src='https://img.shields.io/badge/macOS-000000?style=&logo=apple&logoColor=white'></a>
  <a href='https://www.linux.org/'><img alt='Linux' height='30' src='https://img.shields.io/badge/Linux-FCC624?style=&logo=linux&logoColor=333333'></a>
  <a href='https://www.android.com/'><img alt='Android' height='30' src='https://img.shields.io/badge/Android-3DDC84?style=&logo=android&logoColor=white'></a>
  <a href='https://www.apple.com/ios'><img alt='iOS' height='30' src='https://img.shields.io/badge/iOS-000000?style=&logo=apple&logoColor=white'></a>
  <a href='#---'><img alt='Web' height='30' src='https://img.shields.io/badge/Web-FFFFFF?style=&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzMzMzMzMyIgZD0iTTEyIDEuOTk4YzUuNTI0IDAgMTAuMDAyIDQuNDc4IDEwLjAwMiAxMC4wMDJjMCA1LjUyMy00LjQ3OCAxMC0xMC4wMDIgMTBTMiAxNy41MjMgMiAxMkMxLjk5OSA2LjQ3NiA2LjQ3NiAxLjk5OCAxMiAxLjk5OE0xNC45NCAxNi41SDkuMDYxYy42NTIgMi40MTUgMS43ODYgNC4wMDIgMi45NCA0LjAwMnMyLjI4Ni0xLjU4OCAyLjkzOC00LjAwMm0tNy40MyAwSDQuNzg1YTguNTMgOC41MyAwIDAgMCA0LjA5NSAzLjQxYy0uNTIyLS44Mi0uOTUzLTEuODQ2LTEuMjctMy4wMTV6bTExLjcwNSAwaC0yLjcyMmMtLjMyNCAxLjMzNS0uNzkyIDIuNS0xLjM3MyAzLjQxMWE4LjUzIDguNTMgMCAwIDAgMy45MS0zLjEyN3pNNy4wOTQgMTBIMy43MzZsLS4wMDUuMDE3QTguNSA4LjUgMCAwIDAgMy41IDEyYTguNSA4LjUgMCAwIDAgLjU0NCAzaDMuMTczQTIwIDIwIDAgMCAxIDcgMTJjMC0uNjg0LjAzMi0xLjM1NC4wOTUtMi4wMDFtOC4zMDMgMEg4LjYwM2ExOSAxOSAwIDAgMCAuMTM1IDVoNi41MjRhMTkgMTkgMCAwIDAgLjEzNS01bTQuODY4IDBoLTMuMzU4Yy4wNjIuNjQ3LjA5NSAxLjMxNy4wOTUgMmEyMCAyMCAwIDAgMS0uMjE4IDNoMy4xNzNhOC41IDguNSAwIDAgMCAuNTQ1LTNjMC0uNjg5LS4wODItMS4zNTktLjIzNy0yTTguODggNC4wODhsLS4wMjMuMDA4QTguNTMgOC41MyAwIDAgMCA0LjI1IDguNWgzLjA0OGMuMzE0LTEuNzUyLjg2LTMuMjc4IDEuNTgzLTQuNDFtMy4xMi0uNTkxbC0uMTE3LjAwNUMxMC42MiAzLjYyIDkuMzk3IDUuNjIxIDguODMgOC41aDYuMzQyYy0uNTY2LTIuODctMS43ODMtNC44NjktMy4wNDUtNC45OTV6bTMuMTIuNTlsLjEwNi4xNzVjLjY3IDEuMTEyIDEuMTc3IDIuNTcyIDEuNDc1IDQuMjM3aDMuMDQ4YTguNTMgOC41MyAwIDAgMC00LjMzOS00LjI5eiIvPjwvc3ZnPg=='></a>

  <!-- ACTIONS -->
  ##
  <a href='#gettingstarted'><img alt='Get Started' height='40' src='https://img.shields.io/badge/Get%20Started-4aa4e7?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNy42MDggNC42MTVhLjc1Ljc1IDAgMCAwLTEuMTA4LjY1OXYxMy40NTJhLjc1Ljc1IDAgMCAwIDEuMTA4LjY1OWwxMi4zNjItNi43MjZhLjc1Ljc1IDAgMCAwIDAtMS4zMTh6TTUgNS4yNzRjMC0xLjcwNyAxLjgyNi0yLjc5MiAzLjMyNS0xLjk3N2wxMi4zNjIgNi43MjdjMS41NjYuODUyIDEuNTY2IDMuMSAwIDMuOTUyTDguMzI1IDIwLjcwMkM2LjgyNiAyMS41MTggNSAyMC40MzIgNSAxOC43MjZ6Ii8+PC9zdmc+'></a>
  <a href='https://github.com/deantumabcao/README_Template/releases/latest'><img alt='Latest Version' height='40' src='https://img.shields.io/github/v/release/deantumabcaofhs/A_Plane?label=Latest%20Version&color=64b75d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMy41IDEyYTguNSA4LjUgMCAxIDEgMTcgMGE4LjUgOC41IDAgMCAxLTE3IDBNMTIgMkM2LjQ3NyAyIDIgNi40NzcgMiAxMnM0LjQ3NyAxMCAxMCAxMHMxMC00LjQ3NyAxMC0xMFMxNy41MjMgMiAxMiAybTUuNSA2LjI1YS43NS43NSAwIDAgMC0xLjUgMFY5YTUgNSAwIDAgMC00LTJhNC45OSA0Ljk5IDAgMCAwLTMuODEgMS43NjJhLjc1Ljc1IDAgMSAwIDEuMTQzLjk3MmEzLjUgMy41IDAgMCAxIDUuODMuNzY2SDEzLjc1YS43NS43NSAwIDAgMCAwIDEuNWgzYS43NS43NSAwIDAgMCAuNzUtLjc1ek03LjI1IDE2LjVhLjc1Ljc1IDAgMCAxLS43NS0uNzV2LTNhLjc1Ljc1IDAgMCAxIC43NS0uNzVoM2EuNzUuNzUgMCAwIDEgMCAxLjVIOC44MzdhMy41IDMuNSAwIDAgMCA1LjgzLjc2N2EuNzUuNzUgMCAwIDEgMS4xNDIuOTcyQTQuOTkgNC45OSAwIDAgMSAxMiAxN2E1IDUgMCAwIDEtNC0ydi43NWEuNzUuNzUgMCAwIDEtLjc1Ljc1Ii8+PC9zdmc+'></a>
  <a href='/LICENSE'><img alt='License' height='40' src='https://img.shields.io/github/license/deantumabcao/README_Template?label=License&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0zIDMuNzVBLjc1Ljc1IDAgMCAxIDMuNzUgM2gxNi41YS43NS43NSAwIDAgMSAwIDEuNWgtMS4wNDJsMi43MzcgNi43MTdBLjguOCAwIDAgMSAyMiAxMS41YTMuNSAzLjUgMCAxIDEtNyAwYS44LjggMCAwIDEgLjA1NS0uMjgzTDE3Ljc5MiA0LjVIMTIuNzV2MTJoNGEyLjI1IDIuMjUgMCAwIDEgMCA0LjVINy4yNTNhMi4yNSAyLjI1IDAgMCAxIDAtNC41aDMuOTk3di0xMkg2LjIwOGwyLjczNyA2LjcxN0EuOC44IDAgMCAxIDkgMTEuNWEzLjUgMy41IDAgMSAxLTcgMGEuOC44IDAgMCAxIC4wNTUtLjI4M0w0Ljc5MiA0LjVIMy43NUEuNzUuNzUgMCAwIDEgMyAzLjc1bTMuNTAzIDE1YzAgLjQxNC4zMzYuNzUuNzUuNzVoOS40OTdhLjc1Ljc1IDAgMCAwIDAtMS41SDcuMjUzYS43NS43NSAwIDAgMC0uNzUuNzVtLjg1Mi02LjVoLTMuNzFhMiAyIDAgMCAwIDMuNzEgMG0tLjIyLTEuNUw1LjUgNi43MzhMMy44NjUgMTAuNzV6TTE4LjUgMTMuNWEyIDIgMCAwIDAgMS44NTUtMS4yNWgtMy43MUEyIDIgMCAwIDAgMTguNSAxMy41bS0xLjYzNS0yLjc1aDMuMjdMMTguNSA2LjczOHoiLz48L3N2Zz4='></a>
  <!-- 👆change the link to be your repository see choosealicense.com -->

<a href=''><img alt='Stars' height='25' src='https://img.shields.io/github/stars/deantumabcao/README_Template'></a>

</div>


---



<!-- TABLE OF CONTENTS -->
<details>
  <summary><h2>📑Table of Contents</h2></summary>
  <ol>
    <li>
      <a href='#news'>📰 News</a>
    </li>
    <li>
      <a href='#trailer'>🎬 Trailer</a>
    </li>
    <li>
      <a href='#gallery'>🖼️ Gallery</a>
    </li>
    <li>
      <a href='#features'>⚙️ Features</a>
    </li>
    <li>
      <a href='#roadmap'>🗓️ Roadmap</a>
    </li>
    <li>
      <a href='#getstarted'>▶️ Get Started</a>
    </li>
    <li>
      <a href='#userguide'>📖 User Guide</a>
    </li>
    <li>
      <a href='#help'>❓ Help</a>
    </li>
    <li>
      <a href='#acknowledgements'>🙌 Acknowledgements</a>
    </li>
    <li>
      <a href='#contributing2'>🤝 Contributing</a>
    </li>
  </ol>
</details>



<a id='news'></a>
## 📰 News
* **10/4/2024**: Something happened!
* **m/d/y**: Something important goes here.



<a id='trailer'></a>
## 🎬 Trailer
This video belongs to Epic Games. I use this as an example.  

https://github.com/user-attachments/assets/e56af57c-b6f9-4db8-b529-ec07b3172f1e


<a id='gallery'></a>
## 🖼️ Gallery
These images belong to Epic Games. I use them as examples.  
<img alt='example' src='https://cdn2.unrealengine.com/en-23br-c4s1-keyart-social-social-1920x1080-bac61b6f1cc4.jpg' width=49%> <!-- example -->
<img alt='example' src='https://cdn2.unrealengine.com/download-key-art2-1920x1080-21e209f6bab4.jpg' width=49%> <!-- example -->
<img alt='example' src='https://cdn2.unrealengine.com/fortnite-falcon-scout-gameplay-2-1920x1080-65f8bb6b4dfd.jpg' width=49%> <!-- example -->
<img alt='example' src='https://cdn2.unrealengine.com/fortnite-battle-royale-chapter-5-season-1-screenshot-a-1920x1080-91f507e691cb.jpg' width=49%> <!-- example -->
<!-- TEMPLATE: <img alt='example' src='.png' width=100%> -->



<a id='features'></a>
## ⚙️ Features
<a href='#---'><img alt='text' height='25' src='https://img.shields.io/badge/Singleplayer-7F7F7F?style=&logo=&logoColor=white'></a>
<a href='#---'><img alt='text' height='25' src='https://img.shields.io/badge/Action-7F7F7F?style=&logo=&logoColor=white'></a>
<a href='#---'><img alt='text' height='25' src='https://img.shields.io/badge/Simulation-7F7F7F?style=&logo=&logoColor=white'></a>

* Lorem ipsum odor amet, consectetuer adipiscing elit. Ornare vitae lacinia volutpat volutpat augue euismod.
* Lorem ipsum odor amet, consectetuer adipiscing elit. Gravida porttitor nullam ornare blandit at duis lacinia. Conubia magnis odio lobortis a nisi tristique.
* Lorem ipsum odor amet, consectetuer adipiscing elit. Lobortis condimentum ornare enim bibendum vivamus conubia leo. Penatibus himenaeos fusce auctor ad hendrerit metus tempus lectus. Semper auctor bibendum cursus urna hac pretium.



<a id='roadmap'></a>
## 🗓️ Roadmap
- [x] **9/5/2024**: example <!-- example -->
- [ ] **2025**: example 2 <!-- example -->
  - [ ] feature
  - [ ] feature 2



<a id='getstarted'></a>
## ▶️ Get Started
### Using

* Download and run the installer for your specific operating system from <a href='https://github.com/deantumabcao/README_Template/releases'><img alt='Releases' height='25' src='https://img.shields.io/badge/Releases-64b75d?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xOC4yNSAyMC41YS43NS43NSAwIDEgMSAwIDEuNWwtMTMgLjAwNWEuNzUuNzUgMCAxIDEgMC0xLjV6TTExLjY0OCAyLjAxNGwuMTAyLS4wMDdhLjc1Ljc1IDAgMCAxIC43NDMuNjQ4bC4wMDcuMTAybC0uMDAxIDEzLjY4NWwzLjcyMi0zLjcyYS43NS43NSAwIDAgMSAuOTc2LS4wNzNsLjA4NS4wNzNhLjc1Ljc1IDAgMCAxIC4wNzIuOTc2bC0uMDczLjA4NGwtNC45OTcgNC45OTdhLjc1Ljc1IDAgMCAxLS45NzYuMDczbC0uMDg1LS4wNzNsLTUuMDAzLTQuOTk2YS43NS43NSAwIDAgMSAuOTc2LTEuMTM0bC4wODQuMDcybDMuNzE5IDMuNzE0TDExIDIuNzU2YS43NS43NSAwIDAgMSAuNjQ4LS43NDNsLjEwMi0uMDA3eiIvPjwvc3ZnPg=='></a>.  
Download and run a <a href='https://github.com/deantumabcao/README_Template/releases/latest'><img alt='Latest Version' height='20' src='https://img.shields.io/github/v/release/deantumabcaofhs/A_Plane?label=Latest%20Version&color=64b75d&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMy41IDEyYTguNSA4LjUgMCAxIDEgMTcgMGE4LjUgOC41IDAgMCAxLTE3IDBNMTIgMkM2LjQ3NyAyIDIgNi40NzcgMiAxMnM0LjQ3NyAxMCAxMCAxMHMxMC00LjQ3NyAxMC0xMFMxNy41MjMgMiAxMiAybTUuNSA2LjI1YS43NS43NSAwIDAgMC0xLjUgMFY5YTUgNSAwIDAgMC00LTJhNC45OSA0Ljk5IDAgMCAwLTMuODEgMS43NjJhLjc1Ljc1IDAgMSAwIDEuMTQzLjk3MmEzLjUgMy41IDAgMCAxIDUuODMuNzY2SDEzLjc1YS43NS43NSAwIDAgMCAwIDEuNWgzYS43NS43NSAwIDAgMCAuNzUtLjc1ek03LjI1IDE2LjVhLjc1Ljc1IDAgMCAxLS43NS0uNzV2LTNhLjc1Ljc1IDAgMCAxIC43NS0uNzVoM2EuNzUuNzUgMCAwIDEgMCAxLjVIOC44MzdhMy41IDMuNSAwIDAgMCA1LjgzLjc2N2EuNzUuNzUgMCAwIDEgMS4xNDIuOTcyQTQuOTkgNC45OSAwIDAgMSAxMiAxN2E1IDUgMCAwIDEtNC0ydi43NWEuNzUuNzUgMCAwIDEtLjc1Ljc1Ii8+PC9zdmc+'></a> installer to access the recommended *newest* features and fixes.

* Read the [📖 User Guide](#userguide) to learn how you can use this product.


### Contributing
* Read [🤝 Contributing](#contributing2) to learn how to make changes on GitHub and locally
* Project-specific instructions



<a id='userguide'></a>
## 📖 User Guide
<details>
  <summary><b>Details</b></summary>
Lorem ipsum odor amet, consectetuer adipiscing elit. Lobortis condimentum ornare enim bibendum vivamus conubia leo. Penatibus himenaeos fusce auctor ad hendrerit metus tempus lectus. Semper auctor bibendum cursus urna hac pretium. <!-- example -->
<h4>Chapter</h4>
<ul>
  <li>Lorem ipsum odor amet, consectetuer adipiscing elit. Eget ipsum mattis dictum curae hendrerit imperdiet.</li> <!-- example -->
</ul>
</details>



<a id='help'></a>
## ❓ Help



<a id='acknowledgements'></a>
## 🙌 Acknowledgements
* [Dean Tumabcao](https://github.com/deantumabcao)
* This README is inspired from [@othneildrew](https://github.com/othneildrew)'s [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

### Made with
<a href='https://www.java.com'><img alt='Java' height='25' src='https://img.shields.io/badge/Java-%23ED8B00.svg?style=&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNTYgMzQ2Ij48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTgyLjU1NCAyNjcuNDczcy0xMy4xOTggNy42NzUgOS4zOTMgMTAuMjcyYzI3LjM2OSAzLjEyMiA0MS4zNTYgMi42NzUgNzEuNTE3LTMuMDM0YzAgMCA3LjkzIDQuOTcyIDE5LjAwMyA5LjI3OWMtNjcuNjExIDI4Ljk3Ny0xNTMuMDE5LTEuNjc5LTk5LjkxMy0xNi41MTdtLTguMjYyLTM3LjgxNHMtMTQuODAzIDEwLjk1OCA3LjgwNSAxMy4yOTZjMjkuMjM2IDMuMDE2IDUyLjMyNCAzLjI2MyA5Mi4yNzYtNC40M2MwIDAgNS41MjYgNS42MDIgMTQuMjE1IDguNjY2Yy04MS43NDcgMjMuOTA0LTE3Mi43OTggMS44ODUtMTE0LjI5Ni0xNy41MzIiLz48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTE0My45NDIgMTY1LjUxNWMxNi42NiAxOS4xOC00LjM3NyAzNi40NC00LjM3NyAzNi40NHM0Mi4zMDEtMjEuODM3IDIyLjg3NC00OS4xODNjLTE4LjE0NC0yNS41LTMyLjA1OS0zOC4xNzIgNDMuMjY4LTgxLjg1OGMwIDAtMTE4LjIzOCAyOS41My02MS43NjUgOTQuNiIvPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMjMzLjM2NCAyOTUuNDQyczkuNzY3IDguMDQ3LTEwLjc1NyAxNC4yNzNjLTM5LjAyNiAxMS44MjMtMTYyLjQzMiAxNS4zOTMtMTk2LjcxNC40NzFjLTEyLjMyMy01LjM2IDEwLjc4Ny0xMi44IDE4LjA1Ni0xNC4zNjJjNy41ODEtMS42NDQgMTEuOTE0LTEuMzM3IDExLjkxNC0xLjMzN2MtMTMuNzA1LTkuNjU1LTg4LjU4MyAxOC45NTctMzguMDM0IDI3LjE1YzEzNy44NTMgMjIuMzU2IDI1MS4yOTItMTAuMDY2IDIxNS41MzUtMjYuMTk1TTg4LjkgMTkwLjQ4cy02Mi43NzEgMTQuOTEtMjIuMjI4IDIwLjMyM2MxNy4xMTggMi4yOTIgNTEuMjQzIDEuNzc0IDgzLjAzLS44OWMyNS45NzgtMi4xOSA1Mi4wNjMtNi44NSA1Mi4wNjMtNi44NXMtOS4xNiAzLjkyMy0xNS43ODcgOC40NDhjLTYzLjc0NCAxNi43NjUtMTg2Ljg4NiA4Ljk2Ni0xNTEuNDM1LTguMTgzYzI5Ljk4MS0xNC40OTIgNTQuMzU4LTEyLjg0OCA1NC4zNTgtMTIuODQ4bTExMi42MDUgNjIuOTQyYzY0LjgtMzMuNjcyIDM0LjgzOS02Ni4wMyAxMy45MjctNjEuNjdjLTUuMTI2IDEuMDY2LTcuNDExIDEuOTktNy40MTEgMS45OXMxLjkwMy0yLjk4IDUuNTM3LTQuMjdjNDEuMzctMTQuNTQ1IDczLjE4NyA0Mi44OTctMTMuMzU1IDY1LjY0N2MwIC4wMDEgMS4wMDMtLjg5NSAxLjMwMi0xLjY5NyIvPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMTYyLjQzOS4zNzFzMzUuODg3IDM1LjktMzQuMDM3IDkxLjEwMWMtNTYuMDcxIDQ0LjI4Mi0xMi43ODYgNjkuNTMtLjAyMyA5OC4zNzdjLTMyLjczLTI5LjUzLTU2Ljc1LTU1LjUyNi00MC42MzUtNzkuNzJDMTExLjM5NSA3NC42MTIgMTc2LjkxOCA1Ny4zOTMgMTYyLjQzOS4zNyIvPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNOTUuMjY4IDM0NC42NjVjNjIuMTk5IDMuOTgyIDE1Ny43MTItMi4yMDkgMTU5Ljk3NC0zMS42NGMwIDAtNC4zNDggMTEuMTU4LTUxLjQwNCAyMC4wMThjLTUzLjA4OCA5Ljk5LTExOC41NjQgOC44MjQtMTU3LjM5OSAyLjQyMWMuMDAxIDAgNy45NSA2LjU4IDQ4LjgzIDkuMjAxIi8+PC9zdmc+&logoColor=white'></a>
<a href='https://www.python.org/'><img alt='Python' height='25' src='https://img.shields.io/badge/Python-3670A0.svg?style=&logo=python&logoColor=white'></a>
<a href='https://www.jetbrains.com/idea/'><img alt='IntelliJ IDEA' height='25' src='https://img.shields.io/badge/IntelliJ%20IDEA-2b2d30.svg?style=&logo=intellij-idea&logoColor=white'></a>
<a href='https://media.tenor.com/o_5RQarGvJ0AAAAM/kiss.gif'><img alt='Love' height='25' src='https://img.shields.io/badge/Love-FF0000.svg?style=&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Im0xMi44MiA1LjU4bC0uODIuODIybC0uODI0LS44MjRhNS4zNzUgNS4zNzUgMCAxIDAtNy42MDEgNy42MDJsNy44OTUgNy44OTVhLjc1Ljc1IDAgMCAwIDEuMDYgMGw3LjkwMi03Ljg5N2E1LjM3NiA1LjM3NiAwIDAgMC0uMDAxLTcuNTk5YTUuMzggNS4zOCAwIDAgMC03LjYxMSAwbTYuNTQ4IDYuNTRMMTIgMTkuNDg1TDQuNjM1IDEyLjEyYTMuODc1IDMuODc1IDAgMSAxIDUuNDgtNS40OGwxLjM1OCAxLjM1N2EuNzUuNzUgMCAwIDAgMS4wNzMtLjAxMkwxMy44OCA2LjY0YTMuODggMy44OCAwIDAgMSA1LjQ4NyA1LjQ4Ii8+PC9zdmc+'></a>



<a id='contributing2'></a>
## 🤝 Contributing
<a href='/LICENSE'><img alt='License' height='25' src='https://img.shields.io/github/license/deantumabcao/README_Template?label=License&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0zIDMuNzVBLjc1Ljc1IDAgMCAxIDMuNzUgM2gxNi41YS43NS43NSAwIDAgMSAwIDEuNWgtMS4wNDJsMi43MzcgNi43MTdBLjguOCAwIDAgMSAyMiAxMS41YTMuNSAzLjUgMCAxIDEtNyAwYS44LjggMCAwIDEgLjA1NS0uMjgzTDE3Ljc5MiA0LjVIMTIuNzV2MTJoNGEyLjI1IDIuMjUgMCAwIDEgMCA0LjVINy4yNTNhMi4yNSAyLjI1IDAgMCAxIDAtNC41aDMuOTk3di0xMkg2LjIwOGwyLjczNyA2LjcxN0EuOC44IDAgMCAxIDkgMTEuNWEzLjUgMy41IDAgMSAxLTcgMGEuOC44IDAgMCAxIC4wNTUtLjI4M0w0Ljc5MiA0LjVIMy43NUEuNzUuNzUgMCAwIDEgMyAzLjc1bTMuNTAzIDE1YzAgLjQxNC4zMzYuNzUuNzUuNzVoOS40OTdhLjc1Ljc1IDAgMCAwIDAtMS41SDcuMjUzYS43NS43NSAwIDAgMC0uNzUuNzVtLjg1Mi02LjVoLTMuNzFhMiAyIDAgMCAwIDMuNzEgMG0tLjIyLTEuNUw1LjUgNi43MzhMMy44NjUgMTAuNzV6TTE4LjUgMTMuNWEyIDIgMCAwIDAgMS44NTUtMS4yNWgtMy43MUEyIDIgMCAwIDAgMTguNSAxMy41bS0xLjYzNS0yLjc1aDMuMjdMMTguNSA2LjczOHoiLz48L3N2Zz4='></a>
<a href='https://github.com/deantumabcao/README_Template/graphs/contributors'><img alt='Contributors' height='25' src='https://img.shields.io/github/contributors-anon/deantumabcao/README_Template?label=Contributors&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xNC43NTQgMTBjLjk2NiAwIDEuNzUuNzg0IDEuNzUgMS43NXY0Ljc0OWE0LjUwMSA0LjUwMSAwIDAgMS05LjAwMiAwVjExLjc1YzAtLjk2Ni43ODMtMS43NSAxLjc1LTEuNzV6bTAgMS41SDkuMjUyYS4yNS4yNSAwIDAgMC0uMjUuMjV2NC43NDlhMy4wMDEgMy4wMDEgMCAwIDAgNi4wMDIgMFYxMS43NWEuMjUuMjUgMCAwIDAtLjI1LS4yNU0zLjc1IDEwaDMuMzgxYTIuNzQgMi43NCAwIDAgMC0uNjE4IDEuNUgzLjc1YS4yNS4yNSAwIDAgMC0uMjUuMjV2My4yNDlhMi41IDIuNSAwIDAgMCAzLjA4MiAyLjQzM2MuMDg1LjUwNC4yNC45ODUuNDUzIDEuNDMyUTYuNTM5IDE4Ljk5OSA2IDE5YTQgNCAwIDAgMS00LTQuMDAxVjExLjc1YzAtLjk2Ni43ODQtMS43NSAxLjc1LTEuNzVtMTMuMTI1IDBoMy4zNzVjLjk2NiAwIDEuNzUuNzg0IDEuNzUgMS43NVYxNWE0IDQgMCAwIDEtNS4wMyAzLjg2NmMuMjE0LS40NDguMzY5LS45MjkuNDU1LTEuNDMzcS4yNzcuMDY2LjU3NS4wNjdhMi41IDIuNSAwIDAgMCAyLjUtMi41di0zLjI1YS4yNS4yNSAwIDAgMC0uMjUtLjI1aC0yLjc1N2EyLjc0IDIuNzQgMCAwIDAtLjYxOC0xLjVNMTIgM2EzIDMgMCAxIDEgMCA2YTMgMyAwIDAgMSAwLTZtNi41IDFhMi41IDIuNSAwIDEgMSAwIDVhMi41IDIuNSAwIDAgMSAwLTVtLTEzIDBhMi41IDIuNSAwIDEgMSAwIDVhMi41IDIuNSAwIDAgMSAwLTVtNi41LjVhMS41IDEuNSAwIDEgMCAwIDNhMS41IDEuNSAwIDAgMCAwLTNtNi41IDFhMSAxIDAgMSAwIDAgMmExIDEgMCAwIDAgMC0ybS0xMyAwYTEgMSAwIDEgMCAwIDJhMSAxIDAgMCAwIDAtMiIvPjwvc3ZnPg=='></a>

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

For more information, see [Contributing to a project - Github Docs](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project).

## [🔝 Back To Top](#readme-top)

<!-- SHIELDS.IO BADGE FORMAT: <a href='#---'><img alt='text' height='25' src='https://img.shields.io/badge/message-000000?style=&logo=&logoColor=white'></a> DONTCOPYHERE-->
<!-- More info at https://shields.io/badges -->
<!-- Premade Badges at https://github.com/Ileriayo/markdown-badges -->
