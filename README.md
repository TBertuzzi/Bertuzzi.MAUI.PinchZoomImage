# Bertuzzi.MAUI.PinchZoomImage

Zoom in on the image with the pinch of your fingers.

A simple way to zoom in and zoom out on your images with MAUI.

 ###### This is the component, works on iOS, Android
 
 **NuGet**

|Name|Info|
| ------------------- | ------------------- | 
|Bertuzzi.MAUI.PinchZoomImage|[![NuGet](https://buildstats.info/nuget/Bertuzzi.MAUI.PinchZoomImage)](https://www.nuget.org/packages/Bertuzzi.MAUI.PinchZoomImage/)|

 
 **Platform Support**

PinchZoomImage is a MAUI library.

## Setup / Usage

Does not require additional configuration. Just install the package in the shared project and use.

You just need to add the reference in your xaml file.

```csharp
  xmlns:pinch="clr-namespace:Bertuzzi.MAUI.PinchZoomImage;assembly=Bertuzzi.MAUI.PinchZoomImage"  
```

Control

Use with the image control

```csharp
 <pinch:PinchZoom>
     <pinch:PinchZoom.Content>
         <Image Source="xxamarin.jpg" />
     </pinch:PinchZoom.Content>
 </pinch:PinchZoom>     
```

The complete example can be downloaded here: 
https://github.com/TBertuzzi/Bertuzzi.MAUI.PinchZoomImage/tree/master/PinchZoomImageMauiSample

Base on my package : https://github.com/TBertuzzi/Xamarin.Forms.PinchZoomImage
