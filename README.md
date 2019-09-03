# LayaAir is an open-source 2D/3D engine

LayaAir use WebGL1.0/WebGL2.0 as graphic API.
LayaAir is designed for high performance games and support TypeScript and JavaScript、ActionScript 3.0 programming language.
LayaAir can develop once, publish for multi target platform(HTML5、Android、Ios、MiniGame).

## LayaAir features

- High performance

LayaAir use GPU graphic API(WebGL1.0/WebGL2.0).
LayaAir is design to be run without Plugin and on embedded system.

- Light weight and easy to use

LayaAir API architecture aim to be simple, easy to handle, concepted to require small size installation. It can run basic and complete need for HTML5 engine.

- Multi-language development support

Build your HTML5 application from ActionScript 3.0、TypeScript、JavaScript project.

- Laya Native

LayaNative is a complete development solution for LayaAir engine to native Apps, such as iOS or Android. LayaNative uses LayaPlayer as the core runtime and uses reflection function to provide developers with a secondary development. You also can use this function to handle docking market on your native applications.And it also provides developers with testApp and build tools to package and publish your project.

- Provide a visual assistance in the development and tool flow

[LayaAirIDE](http://ldc.layabox.com/index.php?m=content&c=index&a=lists&catid=27) offer code development tools and visual editor. Clear workflow make, ergonomic, designed development efficiency.

[Unity Plugin](http://ldc.layabox.com/index.php?m=content&c=index&a=lists&catid=27)  offer resource and scene export with Unity,can let unity project easier migration to LayaAir.

- Open-source and free

our official Layabox Github with complete engine source version, free of charge, including commercial usage.

## general features overview

- 2D

  Vector Renderer、Atlas Texture、Load Manager、HTML Text、Bitmap Fonts、Mask、Filter、Animation Timeline、UI、ParticleSystem、Bones animation、PhysicalSystem
  
- 3D

  Camera、Mesh、ParticleSystem、Multi Light、SkyRender、SkinnedAnimation、PhysicBaseRendering、Shadow、Custom Shader、Trail、PixelLine、
  Physics、Fog

## Beginner usage

#### JS version

```js
    Laya.init(550, 400);
    Laya.stage.scaleMode = "showall";

    var ape = new Laya.Sprite();
    //Loading our monkey
    ape.loadImage("res/apes/monkey2.png");

    Laya.stage.addChild(ape);
```

#### AS version

```as3
    package
    {
        import laya.display.Sprite;
        import laya.display.Stage;

        public class Sprite_DisplayImage
        {
            public function Sprite_DisplayImage()
            {
                Laya.init(550, 400);
      		    Laya.stage.scaleMode = "showall";

                var ape:Sprite = new Sprite();
                //Loading our monkey
                ape.loadImage("res/apes/monkey2.png");

                Laya.stage.addChild(ape);
            }
        }
    }
```

#### TS version

```ts
    /// <reference path="../../libs/LayaAir.d.ts" />
    class Sprite_DisplayImage{

        constructor(){
            Laya.init(550, 400);
            Laya.stage.scaleMode = "showall";

            var ape = new Laya.Sprite();
            //Loading our monkey
            ape.loadImage("res/apes/monkey2.png");

            Laya.stage.addChild(ape);
        }
    }
    new Sprite_DisplayImage();
```

## API Document

- https://layaair.ldc.layabox.com/api2

## Tutorial Document

- https://ldc2.layabox.com/doc/?nav=zh-ts-0-3-0
- https://github.com/layabox/layaair-doc

## Samples Demo

- https://layaair2.ldc2.layabox.com/demo2/

## Business Case 

- https://www.layabox.com/gamelist/

## Offical Community

- http://ask.layabox.com/