# XamarinVideoPlayer

CrossPlatform Video Player  for Xamarin Form iOS, Android, UWP

## Installation

Nuget: https://www.nuget.org/packages/XamarinVideoPlayer/1.0.2

You have to install this for PCL and platform projects and call init functions

## iOS

XamarinVideoPlayer.iOS.VideoRenderer.Init();

## Android

XamarinVideoPlayer.Droid.VideoRenderer.Init();

## UWP release

var assembliesToInclude = new List<Assembly>()
{
     typeof(XamarinVideoPlayer.UWP.VideoRenderer).GetTypeInfo().Assembly,
};
Xamarin.Forms.Forms.Init(e, assembliesToInclude);

## Usage

url = "http ... mp4/av..." or video local filename

XamarinVideoPlayer.VideoView vPlayer = new XamarinVideoPlayer.VideoView { HeightRequest = 250, Source = url };

## XAML

xmlns:video ="clr-namespace:XamarinVideoPlayer;assembly=XamarinVideoPlayer"

<video:VideoView 	HeightRequest="90" WidthRequest="160"	VerticalOptions="End" HorizontalOptions="End" x:Name="VideoViewer"></video:VideoView>

# Note

-Please feel free to contact me

