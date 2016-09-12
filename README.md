# glfw-app

glfwを用いたアプリケーションを簡単に作れるように準備した、テンプレート・プロジェクト。CMakeでコンパイルし実行できる。

## Hot to Build

## ソースコードの取得

```
$ git clone https://github.com/oguna/glfw-app.git
$ cd glfw-app
$ git submodule update --init -- "lib/glfw"
```

## ビルド(Windows / Visual Studio 2015)

```
$ cmake . -G "Visual Studio 14"
$ msbuild glfw-app.sln /p:Configuratino=MinSizeRel /p:Platform=win32
```
