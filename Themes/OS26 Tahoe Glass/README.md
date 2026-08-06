\# Fluid theme for Windows 11 Notification Center Styler



This theme is Designed to make Windows 11 Notification Center look like MacOS Tahoe. Suggestions, and Contributions are welcome!



\*\*Author\*\*: \[WasiXGamer](https://github.com/wasixgamer)



!\[Preview](screenshot.png) 



\## Previews


!\[Preview-1](preview-1.png)

!\[Preview-2](preview-2.png)

!\[Preview-3](preview-3.png)


## Credits, and Usability

The theme is allowed be edited and distributed. If showcasing the style, or its fork, Please give credits to the Theme Author!



\## Theme selection



The theme is integrated into the mod and can be selected directly from the mod's

settings:



\* Open the Windows 11 Notification Center Styler mod in Windhawk.

\* Go to the "Settings" tab.

\* Select the theme and save the settings.



\## Manual installation



The theme styles can also be imported manually. To do that, follow these steps:



\* Open the Windows 11 Notification Center Styler mod in Windhawk.

\* Go to the "Settings" tab and select "Textual mode".

\* Copy the content below to the text box and click "Save settings".



<details>

<summary>Content to import (click to expand)</summary>



```yaml

theme: 'OS26 Tahoe Glass (By WasiXGamer)'

styleConstants:

&#x20; - ''

controlStyles:

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#NotificationCenterGrid

&#x20;   styles:

&#x20;     - CornerRadius=25

&#x20;     - BorderBrush=#69878787

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid

&#x20;   styles:

&#x20;     - BorderBrush:=#69878787

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: Windows.UI.Xaml.Controls.TextBlock

&#x20;   styles:

&#x20;     - FontWeight=Bold

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#NotificationCenterGrid > ActionCenter.NotificationCenterView#NotificationCenterView > Grid#MainGrid > ActionCenter.NotificationListView#MainListView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > ActionCenter.NotificationListViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter > ActionCenter.FlexibleItemView > Grid#MainGrid > Grid#ItemGrid > Grid > Border#ItemOpaquePlating

&#x20;   styles:

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="0.60,1.96" EndPoint="0.40,-0.96"><GradientStop Offset="0.24" Color="#878787"/><GradientStop Offset="0.43" Color="#36000000"/><GradientStop Offset="0.57" Color="#2B000000"/><GradientStop Offset="0.75" Color="#878787"/></LinearGradientBrush>

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer

&#x20;   styles:

&#x20;     - Margin=-10,-45,-10,-13

&#x20;     - Width=325

&#x20;     - Background=transparent

&#x20;     - BorderThickness=0

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ActionCenter.FocusSessionControl#FocusSessionControl > Grid#FocusGrid

&#x20;   styles:

&#x20;     - Visibility=1

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > StackPanel#CalendarHeader

&#x20;   styles:

&#x20;     - Canvas.ZIndex=1

&#x20;     - Margin=0,5,0,-5

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#HeaderButton > ContentPresenter#Text

&#x20;   styles:

&#x20;     - Background=transparent

&#x20;     - CornerRadius=0

&#x20;     - Width=130

&#x20;     - FontSize=13

&#x20;     - Margin=-48,20,48,-20

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > StackPanel#CalendarHeader > Button#DateTextButton > Grid > Border#Border > ContentPresenter#ContentPresenter > TextBlock

&#x20;   styles:

&#x20;     - FontSize=13

&#x20;     - Margin=-6,0,6,0

&#x20; - target: Microsoft.UI.Xaml.Controls.AnimatedIcon#ExpandCollapseButtonIcon

&#x20;   styles:

&#x20;     - FontSize=25

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > Button#ExpandCollapseButton

&#x20;   styles:

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#2D101010"/>

&#x20;     - Margin=10,0,-10,0

&#x20;     - CornerRadius=12

&#x20;     - Width=35

&#x20;     - Height=35

&#x20;     - Canvas.ZIndex=1

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#PreviousButton > ContentPresenter#Text

&#x20;   styles:

&#x20;     - Background=transparent

&#x20;     - Margin=-10,-5,10,5

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#PreviousButton > ContentPresenter#Text > TextBlock

&#x20;   styles:

&#x20;     - FontSize=20

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#NextButton > ContentPresenter#Text

&#x20;   styles:

&#x20;     - Background=transparent

&#x20;     - Margin=-25,-5,25,5

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#NextButton > ContentPresenter#Text > TextBlock

&#x20;   styles:

&#x20;     - FontSize=20

&#x20; - target: ActionCenter.NotificationCenterPage > Grid#RootGrid > Grid#RootContent > Grid#CalendarCenterGrid > ActionCenter.ClockCalendarView#ClockCalendarView > Grid > Grid#CalendarSection > ScrollViewer#CalendarControlScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > CalendarView#CalendarControl > Border > Grid > Grid > Button#PreviousButton > ContentPresenter#Text

&#x20;   styles:

&#x20;     - FontSize=16

&#x20; - target: ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion

&#x20;   styles:

&#x20;     - // \[start of action center customizations]

&#x20;     - // \[background]

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="3.5" TintColor="#761E1E1E"/>

&#x20; - target: ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion

&#x20;   styles:

&#x20;     - // \[Music page bg]

&#x20;     - CornerRadius=25

&#x20;     - Background:=<WindhawkBlur BlurAmount="3.5" TintColor="#761E1E1E"/>

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid > TextBlock#AppNameText

&#x20;   styles:

&#x20;     - FontSize=18  

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid > Image#IconImage

&#x20;   styles:

&#x20;     - Height=25

&#x20;     - Width=25

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid#AlbumTextAndArtContainer > StackPanel#PrimaryAndSecondaryTextContainer

&#x20;   styles:

&#x20;     - Margin=90,-5,-70,5

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid#AlbumTextAndArtContainer > StackPanel#PrimaryAndSecondaryTextContainer > TextBlock#TitleText

&#x20;   styles:

&#x20;     - FontSize=19    

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid#AlbumTextAndArtContainer > StackPanel#PrimaryAndSecondaryTextContainer > TextBlock#SubtitleText

&#x20;   styles:

&#x20;     - FontSize=16    

&#x20; - target: ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > Grid#AlbumTextAndArtContainer > Grid#ThumbnailImage

&#x20;   styles:

&#x20;     - Width=70

&#x20;     - Height=70

&#x20;     - Margin=-240,-5,240,5

&#x20;     - HorizontalAlignment=left  

&#x20; - target: ControlCenter.MediaTransportControls#MediaTransportControls > Grid#MediaTransportControlsRegion > Grid#MediaTransportControlsRoot > ListView#MediaButtonsListView > ItemsPresenter > StackPanel

&#x20;   styles:

&#x20;     - Margin=0.-10,0,-10

&#x20; - target: Windows.UI.Xaml.Controls.Primitives.RepeatButton#PreviousButton > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[Previous button]

&#x20;     - Margin=-10,0,-10,0

&#x20;     - Height=45

&#x20;     - Width=65

&#x20; - target: Windows.UI.Xaml.Controls.Primitives.RepeatButton#PreviousButton > ContentPresenter#ContentPresenter > TextBlock

&#x20;   styles:

&#x20;     - // \[Previous button Font]

&#x20;     - FontSize=30    

&#x20; - target: Button#PlayPauseButton > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[play button]

&#x20;     - Margin=-20,0,-20,0

&#x20;     - Height=45

&#x20;     - Width=65

&#x20; - target: Button#PlayPauseButton > ContentPresenter#ContentPresenter > TextBlock

&#x20;   styles:

&#x20;     - // \[play button Font]

&#x20;     - FontSize=30  

&#x20; - target: Windows.UI.Xaml.Controls.Primitives.RepeatButton#NextButton > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[Next button]

&#x20;     - Margin=-20,0,-20,0

&#x20;     - Height=45

&#x20;     - Width=65

&#x20; - target: Windows.UI.Xaml.Controls.Primitives.RepeatButton#NextButton > ContentPresenter#ContentPresenter > TextBlock

&#x20;   styles:

&#x20;     - // \[Next button Font]

&#x20;     - FontSize=30  



&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > ControlCenter.AccessibleItemContainer > Grid#RootGrid > ContentControl#QuickActionContentControl > ContentPresenter > Grid > ControlCenter.AsyncSlider > Grid > Grid#SliderContainer > Grid#HorizontalTemplate > Rectangle#HorizontalTrackRect

&#x20;   styles:

&#x20;     - RadiusX=6

&#x20;     - RadiusY=6

&#x20;     - Height=15

&#x20;     - Margin=0,-7.5,0,7.5

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > ControlCenter.AccessibleItemContainer > Grid#RootGrid > ContentControl#QuickActionContentControl > ContentPresenter > Grid > ControlCenter.AsyncSlider > Grid > Grid#SliderContainer > Grid#HorizontalTemplate > Rectangle#HorizontalDecreaseRect

&#x20;   styles:

&#x20;     - RadiusX=6

&#x20;     - RadiusY=6

&#x20;     - Margin=0,-7.5,0,7.5

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root

&#x20;   styles:

&#x20;     - CornerRadius=25

&#x20;     - Background:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - Height=auto

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > ControlCenter.AccessibleItemContainer > Grid#RootGrid > ContentControl#QuickActionContentControl > ContentPresenter > Grid > ControlCenter.AsyncSlider > Grid > Grid#SliderContainer > Grid#HorizontalTemplate > Windows.UI.Xaml.Controls.Primitives.Thumb#HorizontalThumb

&#x20;   styles:

&#x20;     - Margin=-5,-7.5,0,7.5

&#x20;     - Height=35

&#x20;     - Width=45

&#x20; - target: GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > Grid > Grid > ControlCenter.PaginatedToggleButton#ToggleButton > ContentPresenter#ContentPresenter@CommonStates

&#x20;   styles:

&#x20;     - CornerRadius=25

&#x20;     - Foreground@Checked:=#0076FF

&#x20;     - Foreground@CheckedPointerOver:=#0076FF

&#x20;     - Foreground@CheckedPressed:=#0076FF

&#x20;     - Foreground@CheckedDisabled:=#0076FF

&#x20;     - Background@Normal:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - Background@PointerOver:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - Background@Pressed:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - Background@Disabled:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - Background@Checked:=<WindhawkBlur BlurAmount="8" TintColor="#78ffffff" TintOpacity="0.8" />

&#x20;     - Background@CheckedPointerOver:=<WindhawkBlur BlurAmount="8" TintColor="#78ffffff" TintOpacity="0.8" />

&#x20;     - Background@CheckedPressed:=<WindhawkBlur BlurAmount="8" TintColor="#78ffffff" TintOpacity="0.8" />



&#x20;     - Background@CheckedDisabled:=<WindhawkBlur BlurAmount="8" TintColor="#78ffffff" TintOpacity="0.8" />

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="-0.02,-0.12" EndPoint="1.04,1.11"><GradientStop Offset="0.13" Color="#8A878787"/><GradientStop Offset="0.3" Color="#691C1C1C"/><GradientStop Offset="0.67" Color="#871C1C1C"/><GradientStop Offset="0.9" Color="#878787"/></LinearGradientBrush>

&#x20; - target: GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > StackPanel > ContentControl > ContentPresenter > Grid > Grid > ControlCenter.PaginatedToggleButton#ToggleButton > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - CornerRadius=25

&#x20;     - Background:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="-0.02,-0.12" EndPoint="1.04,1.11"><GradientStop Offset="0.13" Color="#8A878787"/><GradientStop Offset="0.3" Color="#691C1C1C"/><GradientStop Offset="0.67" Color="#871C1C1C"/><GradientStop Offset="0.9" Color="#878787"/></LinearGradientBrush>

&#x20; - target: Microsoft.UI.Xaml.Controls.PipsPager#QuickActionsPager

&#x20;   styles:

&#x20;     - Visibility=1

&#x20; - target: Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > ControlCenter.AccessibleItemContainer > Grid#RootGrid > ContentControl#QuickActionContentControl > ContentPresenter > Grid > ControlCenter.AsyncSlider > Grid > Grid#SliderContainer > Grid#HorizontalTemplate > Windows.UI.Xaml.Controls.Primitives.Thumb#HorizontalThumb > Border > Windows.UI.Xaml.Shapes.Ellipse#SliderInnerThumb

&#x20;   styles:

&#x20;     - Visibility=1

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#SlidersGroup > ContentPresenter > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsStackPanel > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > ControlCenter.AccessibleItemContainer > Grid#RootGrid > ContentControl#QuickActionContentControl > ContentPresenter > Grid > ControlCenter.AsyncSlider > Grid > Grid#SliderContainer > Grid#HorizontalTemplate > Windows.UI.Xaml.Controls.Primitives.Thumb#HorizontalThumb > Border

&#x20;   styles:

&#x20;     - CornerRadius=16

&#x20;     - Background:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20; - target: ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion

&#x20;   styles:

&#x20;     - Height=auto

&#x20; - target: ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#TogglesGroup > ContentPresenter > ControlCenter.PaginatedGridView > Grid > Border#NextPageSensor

&#x20;   styles:

&#x20;     - Margin=0,400,0,0

&#x20; - target: ControlCenter.ControlCenterPage > Grid#RootGrid > Grid#RootContent > Grid#ControlCenterRegion > ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#TogglesGroup > ContentPresenter > ControlCenter.PaginatedGridView > Grid > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid

&#x20;   styles:

&#x20;     - Margin=0,-100,0,-100

&#x20; - target: GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > Grid > ControlCenter.PaginatedToggleButton#ToggleButton > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[Other Icons]

&#x20;     - Foreground=white

&#x20;     - CornerRadius=25

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="-0.02,-0.12" EndPoint="1.04,1.11"><GradientStop Offset="0.13" Color="#8A878787"/><GradientStop Offset="0.3" Color="#691C1C1C"/><GradientStop Offset="0.67" Color="#871C1C1C"/><GradientStop Offset="0.9" Color="#878787"/></LinearGradientBrush>

&#x20;     - Background:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20; - target: GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[Other Icons]

&#x20;     - CornerRadius=25

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="-0.02,-0.12" EndPoint="1.04,1.11"><GradientStop Offset="0.13" Color="#8A878787"/><GradientStop Offset="0.3" Color="#691C1C1C"/><GradientStop Offset="0.67" Color="#871C1C1C"/><GradientStop Offset="0.9" Color="#878787"/></LinearGradientBrush>

&#x20;     - Background:=<WindhawkBlur BlurAmount="8" TintColor="#2D101010"/>

&#x20; - target: Microsoft.UI.Xaml.Controls.AnimatedIcon

&#x20;   styles:

&#x20;     - // \[The Icon in content boxes like bt icon wifi icon]

&#x20;     - Height=25

&#x20;     - Width=25

&#x20; - target: ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#TogglesGroup > ContentPresenter > ControlCenter.PaginatedGridView > Grid > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsWrapGrid > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > Grid > Grid > ControlCenter.PaginatedToggleButton#SplitL2Button > ContentPresenter#ContentPresenter > FontIcon > Grid > TextBlock

&#x20;   styles:

&#x20;     - // \[The Arrow indicator of opening Wifi and bluetooth panel]

&#x20;     - Margin=20,0,-20,0

&#x20;     - Foreground=white

&#x20; - target: ControlCenter.ControlCenterView#ControlCenterView > Grid#RootGrid > Grid#L1Grid > ContentControl#TogglesGroup > ContentPresenter > ControlCenter.PaginatedGridView > Grid > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsWrapGrid > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > Grid > Grid > ControlCenter.PaginatedToggleButton#ToggleButton

&#x20;   styles:

&#x20;     - // \[CanvasZindex of wifi and bluetooth]

&#x20;     - Canvas.ZIndex=1

&#x20; - target: ContentControl#TogglesGroup > ContentPresenter > ControlCenter.PaginatedGridView > Grid > GridView#RootGridView > Border > ScrollViewer#ScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > ItemsPresenter > ItemsWrapGrid > GridViewItem > Windows.UI.Xaml.Controls.Primitives.ListViewItemPresenter#Root > ContentControl > ContentPresenter > Grid > Grid > ControlCenter.PaginatedToggleButton#SplitL2Button > ContentPresenter#ContentPresenter

&#x20;   styles:

&#x20;     - // \[Wifi and bluetooth icon frame.]

&#x20;     - CornerRadius=25

&#x20;     - Background:=<WindhawkBlur BlurAmount="3.5" TintColor="#2D101010"/>

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="-0.02,-0.12" EndPoint="1.04,1.11"><GradientStop Offset="0.13" Color="#8A878787"/><GradientStop Offset="0.3" Color="#691C1C1C"/><GradientStop Offset="0.67" Color="#871C1C1C"/><GradientStop Offset="0.9" Color="#878787"/></LinearGradientBrush>

&#x20;     - Margin=-50,0,0,0

&#x20; - target: ActionCenter.FlexibleToastView#FlexiblePriorityToastView > Grid#MainGrid > Grid#RevealGrid2 > Border#ToastBackgroundBorder2

&#x20;   styles:

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="0.60,1.96" EndPoint="0.40,-0.96"><GradientStop Offset="0.24" Color="#878787"/><GradientStop Offset="0.43" Color="#36000000"/><GradientStop Offset="0.57" Color="#2B000000"/><GradientStop Offset="0.75" Color="#878787"/></LinearGradientBrush>

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: ActionCenter.ToastCenterView#ToastCenterView > ScrollViewer#ToastCenterScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > Grid#ToastCenterGrid > ActionCenter.FlexibleToastView#FlexiblePriorityToastView3 > Grid#MainGrid > Grid#RevealGrid2 > Border#ToastBackgroundBorder2

&#x20;   styles:

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="0.60,1.96" EndPoint="0.40,-0.96"><GradientStop Offset="0.24" Color="#878787"/><GradientStop Offset="0.43" Color="#36000000"/><GradientStop Offset="0.57" Color="#2B000000"/><GradientStop Offset="0.75" Color="#878787"/></LinearGradientBrush>

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.ToastCenterPage > Grid#ToastCenterMainGrid > ActionCenter.ToastCenterView#ToastCenterView > ScrollViewer#ToastCenterScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > Grid#ToastCenterGrid > ActionCenter.FlexibleToastView#FlexibleNormalToastView > Grid#MainGrid > Grid#RevealGrid2 > Border#ToastBackgroundBorder2

&#x20;   styles:

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="0.60,1.96" EndPoint="0.40,-0.96"><GradientStop Offset="0.24" Color="#878787"/><GradientStop Offset="0.43" Color="#36000000"/><GradientStop Offset="0.57" Color="#2B000000"/><GradientStop Offset="0.75" Color="#878787"/></LinearGradientBrush>

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>

&#x20; - target: ScrollViewer > ScrollContentPresenter > Border > Frame > ContentPresenter > ActionCenter.ToastCenterPage > Grid#ToastCenterMainGrid > ActionCenter.ToastCenterView#ToastCenterView > ScrollViewer#ToastCenterScrollViewer > Border#Root > Grid > ScrollContentPresenter#ScrollContentPresenter > Grid#ToastCenterGrid > ActionCenter.FlexibleToastView#FlexiblePriorityToastView2 > Grid#MainGrid > Grid#RevealGrid2 > Border#ToastBackgroundBorder2

&#x20;   styles:

&#x20;     - BorderBrush:=<LinearGradientBrush StartPoint="0.60,1.96" EndPoint="0.40,-0.96"><GradientStop Offset="0.24" Color="#878787"/><GradientStop Offset="0.43" Color="#36000000"/><GradientStop Offset="0.57" Color="#2B000000"/><GradientStop Offset="0.75" Color="#878787"/></LinearGradientBrush>

&#x20;     - CornerRadius=25

&#x20;     - BorderThickness=2

&#x20;     - Background:=<WindhawkBlur BlurAmount="16" TintColor="#761E1E1E"/>


```

</details>

