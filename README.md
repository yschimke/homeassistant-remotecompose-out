# Accessibility Report

_Auto-generated from `compose-preview/a11y/pr`. 131 preview(s) across 3 module(s) · 200 error(s) · 99 warning(s) · 163 info._

Browse inline; image URLs are pinned to the commit SHA on the baseline branch so links keep resolving after merge.

## app

### `Play_Phone_01_HomeLight` · `spec:width=411dp,height=731dp,dpi=320`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Play_Phone_01_HomeLight_play_phone_home_light-27629862.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 2 other item(s). |

### `Play_Phone_02_HomeDark` · `spec:width=411dp,height=731dp,dpi=320`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Play_Phone_02_HomeDark_play_phone_home_dark-87829c7b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 2 other item(s). |

### `Play_Tablet10_01_Home` · `spec:width=800dp,height=1280dp,dpi=224`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Play_Tablet10_01_Home_play_10_inch_home-7ca1827e.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 2 other item(s). |

### `Play_Tablet7_01_Home` · `spec:width=600dp,height=960dp,dpi=240`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Play_Tablet7_01_Home_play_7_inch_home-eb94cb4a.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 1 other item(s). |

### `Screen_DashboardView`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Screen_DashboardView_dashboard_view-c60327e8.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 2 other item(s). |

### `Screen_DashboardView_PhoneLandscapeMedium`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/Screen_DashboardView_PhoneLandscapeMedium_dashboard_view_phone_landscape_medium-8837149f.a11y.png" width="400" />

_No findings._

### `Screen_DashboardView_ThemeStyle`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/app/ee.schimke.terrazzo.previews.ScreenPreviewsKt.Screen_DashboardView_ThemeStyle_dashboard · theme.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "dashboard-card:grid" is identical to that of 2 other item(s). |

## previews

### `Button_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/ee.schimke.ha.previews.CardPreviewsKt.Button_Dark_button (dark).a11y.png" width="400" />

_No findings._

### `Button_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/ee.schimke.ha.previews.CardPreviewsKt.Button_Light_button (light).a11y.png" width="400" />

_No findings._

### `CardPreviewMatrix_Entities`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/CardPreviewMatrix_Entities_matrix_entities-898c466b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 7 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 8 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 9 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 21dp. Consider making the height of this touch target 48dp or larger. |
| 10 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 37dp. Consider making the height of this touch target 48dp or larger. |
| 11 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 21dp. Consider making the height of this touch target 48dp or larger. |
| 12 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 21dp. Consider making the height of this touch target 48dp or larger. |
| 13 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 37dp. Consider making the height of this touch target 48dp or larger. |
| 14 | ERROR | TouchTargetSizeCheck | android.view.View  desc="Living Room" | This item's height is 28dp. Consider making the height of this touch target 48dp or larger. |
| 15 | ERROR | TouchTargetSizeCheck | android.view.View  desc="Office lamp Office lamp" | This item's height is 30dp. Consider making the height of this touch target 48dp or larger. |
| 16 | ERROR | TouchTargetSizeCheck | android.view.View  desc="Coffee maker Coffee maker" | This item's height is 30dp. Consider making the height of this touch target 48dp or larger. |
| 17 | ERROR | TouchTargetSizeCheck | android.view.View  desc="Front door" | This item's height is 30dp. Consider making the height of this touch target 48dp or larger. |
| 18 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 2 other item(s). |
| 19 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Terrazzo slot" is identical to that of 1 other item(s). |
| 20 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Office lamp, Office lamp, Off" is identical to that of 1 other item(s). |
| 21 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Living Room" is identical to that of 1 other item(s). |

### `CardPreviewMatrix_Logbook`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/CardPreviewMatrix_Logbook_matrix_logbook-1e109936.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 4 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Garage motion" | This non-clickable item's speakable text: "Garage motion" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Front door" | This non-clickable item's speakable text: "Front door" is identical to that of 5 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Terrazzo slot" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Off" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "400" is identical to that of 1 other item(s). |

### `CardPreviewMatrix_Statistic`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/CardPreviewMatrix_Statistic_matrix_statistic-3c6a1a49.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Terrazzo slot" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "21.4" is identical to that of 2 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "°C" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "400" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Living Room" is identical to that of 2 other item(s). |

### `CardPreviewMatrix_Tile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/CardPreviewMatrix_Tile_matrix_tile-3b5ef920.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 37dp. Consider making the height of this touch target 48dp or larger. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 37dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 2 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Terrazzo slot" is identical to that of 1 other item(s). |

### `CardPreviewMatrix_WeatherForecast`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/CardPreviewMatrix_WeatherForecast_matrix_weather_forecast-ae933bbe.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | androidx.compose.remote.player.view.RemoteComposePlayer | This item may not have a label readable by screen readers. |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "11.2 °C" is identical to that of 2 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Wind" | This non-clickable item's speakable text: "Wind" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sat" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Terrazzo slot" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Partlycloudy" | This non-clickable item's speakable text: "Partlycloudy" is identical to that of 5 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Humidity" | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |
| 10 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Forecast Home" is identical to that of 2 other item(s). |
| 11 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Thu" is identical to that of 1 other item(s). |
| 12 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Feels" | This non-clickable item's speakable text: "Feels" is identical to that of 1 other item(s). |
| 13 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sun" is identical to that of 1 other item(s). |
| 14 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Mon" is identical to that of 1 other item(s). |
| 15 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Pressure" | This non-clickable item's speakable text: "Pressure" is identical to that of 1 other item(s). |
| 16 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "400" is identical to that of 1 other item(s). |
| 17 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Fri" is identical to that of 1 other item(s). |

### `Dashboard3dPrintingMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Dashboard3dPrintingMobile_dashboard_3d_printing_mobile-2701c9cf.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Status, Status, Idle" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "Idle" is identical to that of 1 other item(s). |
| 3 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Progress, Progress, 0 %" is identical to that of 1 other item(s). |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Remaining, Remaining, 0 h" is identical to that of 1 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Stage, Stage, Idle" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "idle" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "🖨️ P2s" is identical to that of 1 other item(s). |
| 8 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Online, Online, On" is identical to that of 1 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |

### `Dashboard3dPrintingTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Dashboard3dPrintingTablet_dashboard_3d_printing_tablet-d15705fe.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Status, Status, Idle" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "Idle" is identical to that of 1 other item(s). |
| 3 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Progress, Progress, 0 %" is identical to that of 1 other item(s). |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Remaining, Remaining, 0 h" is identical to that of 1 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Stage, Stage, Idle" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "idle" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "🖨️ P2s" is identical to that of 1 other item(s). |
| 8 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Online, Online, On" is identical to that of 1 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |

### `DashboardClimateMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardClimateMobile_dashboard_climate_mobile-bdcd432b.a11y.png" width="400" />

_No findings._

### `DashboardClimateTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardClimateTablet_dashboard_climate_tablet-456c7098.a11y.png" width="400" />

_No findings._

### `DashboardEnergyMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardEnergyMobile_dashboard_energy_mobile-47191266.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "rate:" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "p/kWh" is identical to that of 2 other item(s). |

### `DashboardEnergyTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardEnergyTablet_dashboard_energy_tablet-e2041a44.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "rate:" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "p/kWh" is identical to that of 2 other item(s). |

### `DashboardGithubMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardGithubMobile_dashboard_github_mobile-8f04a7c1.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 4 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 5 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 6 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 7 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 8 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 9 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 10 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 11 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 12 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 13 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 14 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 15 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 16 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 17 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 18 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 19 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 20 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 21 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 22 | WARNING | DuplicateSpeakableTextCheck | android.widget.Button | This clickable item's speakable text: "View on GitHub" is identical to that of 2 other item(s). |
| 23 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "from" is identical to that of 1 other item(s). |
| 24 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "come" is identical to that of 1 other item(s). |
| 25 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "/" is identical to that of 2 other item(s). |
| 26 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 27 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "GitHub" is identical to that of 1 other item(s). |
| 28 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "no recent commit data" is identical to that of 1 other item(s). |
| 29 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "the" is identical to that of 2 other item(s). |
| 30 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "build" is identical to that of 1 other item(s). |
| 31 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "HA" is identical to that of 1 other item(s). |

### `DashboardGithubTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardGithubTablet_dashboard_github_tablet-89194c99.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 4 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 5 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 6 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 7 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 8 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 9 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 10 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 11 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 12 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 13 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 14 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 15 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 16 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 17 | WARNING | DuplicateSpeakableTextCheck | android.widget.Button | This clickable item's speakable text: "View on GitHub" is identical to that of 2 other item(s). |
| 18 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "from" is identical to that of 1 other item(s). |
| 19 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "come" is identical to that of 1 other item(s). |
| 20 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "/" is identical to that of 2 other item(s). |
| 21 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 22 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "GitHub" is identical to that of 1 other item(s). |
| 23 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "no recent commit data" is identical to that of 2 other item(s). |
| 24 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "the" is identical to that of 2 other item(s). |
| 25 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "build" is identical to that of 1 other item(s). |
| 26 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "HA" is identical to that of 1 other item(s). |

### `DashboardMeshcoreMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardMeshcoreMobile_dashboard_meshcore_mobile-30d7121c.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Last" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 1 other item(s). |

### `DashboardMeshcoreTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardMeshcoreTablet_dashboard_meshcore_tablet-e5c71810.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Last" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 1 other item(s). |

### `DashboardNetworksMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardNetworksMobile_dashboard_networks_mobile-d5ee47c2.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "2" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 4 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Mbit/s" is identical to that of 1 other item(s). |

### `DashboardNetworksTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardNetworksTablet_dashboard_networks_tablet-fbca9889.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "2" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 4 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Mbit/s" is identical to that of 1 other item(s). |

### `DashboardSectionCardGridMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardSectionCardGridMobile_dashboard_section_card_grid_mobile-a90a06a6.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "No history in the last 2 days" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Outside · Upstairs · Downstairs · Kitchen" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |

### `DashboardSectionCardGridTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardSectionCardGridTablet_dashboard_section_card_grid_tablet-eac162a7.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "No history in the last 2 days" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Outside · Upstairs · Downstairs · Kitchen" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |

### `DashboardSectionsSpanOneTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardSectionsSpanOneTablet_dashboard_sections_span_1_tablet-56a3e21b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "No history in the last 2 days" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Outside · Upstairs · Downstairs · Kitchen" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |

### `DashboardSecurityMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardSecurityMobile_dashboard_security_mobile-842e09ef.a11y.png" width="400" />

_No findings._

### `DashboardSecurityTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardSecurityTablet_dashboard_security_tablet-d081c9e6.a11y.png" width="400" />

_No findings._

### `DashboardView3dPrintingA1MiniMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingA1MiniMobile_dashboard_3d_printing_view_3_A1_Mini_mobile-5ea13cad.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "Idle" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "idle" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "A1 mini" is identical to that of 1 other item(s). |

### `DashboardView3dPrintingFilamentMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingFilamentMobile_dashboard_3d_printing_view_4_Filament_mobi-3b5ad5f4.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Generic PLA" is identical to that of 3 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Empty" is identical to that of 3 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Bambu PLA Basic" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "AMS" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Slot 1" is identical to that of 1 other item(s). |
| 6 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "AMS active, AMS active, Off" is identical to that of 1 other item(s). |
| 7 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "External spool, External spool, Off" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "-1 %" is identical to that of 3 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "100 %" is identical to that of 5 other item(s). |

### `DashboardView3dPrintingFilamentTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingFilamentTablet_dashboard_3d_printing_view_4_Filament_tabl-09a2b0b7.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Generic PLA" is identical to that of 3 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Empty" is identical to that of 3 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Bambu PLA Basic" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "AMS" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Slot 1" is identical to that of 1 other item(s). |
| 6 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "AMS active, AMS active, Off" is identical to that of 1 other item(s). |
| 7 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "External spool, External spool, Off" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "-1 %" is identical to that of 3 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "100 %" is identical to that of 5 other item(s). |

### `DashboardView3dPrintingP2sMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingP2sMobile_dashboard_3d_printing_view_2_P2s_mobile-7506075a.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "Idle" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "idle" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "A1 mini" is identical to that of 1 other item(s). |

### `DashboardView3dPrintingP2sTablet`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingP2sTablet_dashboard_3d_printing_view_2_P2s_tablet-91c638ec.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View | This non-clickable item's speakable text: "Idle" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "idle" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "A1 mini" is identical to that of 1 other item(s). |

### `DashboardView3dPrintingPrintersMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardView3dPrintingPrintersMobile_dashboard_3d_printing_view_1_Printers_mobi-ea1de9f9.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Stage, Stage, Idle" is identical to that of 1 other item(s). |
| 2 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Status, Status, Idle" is identical to that of 1 other item(s). |
| 3 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Online, Online, On" is identical to that of 1 other item(s). |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Progress, Progress, 0 %" is identical to that of 1 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Remaining, Remaining, 0 h" is identical to that of 1 other item(s). |

### `DashboardViewClimateHomeMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewClimateHomeMobile_dashboard_climate_view_1_Home_mobile-a5e725cc.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "No history in the last 2 days" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Outside · Upstairs · Downstairs · Kitchen" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |

### `DashboardViewEnergyOverviewMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewEnergyOverviewMobile_dashboard_energy_view_1_Overview_mobile-efd95fc9.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "rate:" is identical to that of 2 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 2 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "p/kWh" is identical to that of 2 other item(s). |

### `DashboardViewEnergySunMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewEnergySunMobile_dashboard_energy_view_2_Sun_mobile-9e92f25b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "…" is identical to that of 1 other item(s). |

### `DashboardViewGithubProjectsMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewGithubProjectsMobile_dashboard_github_view_1_Projects_mobile-266d311b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 2 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 3 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 4 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 5 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 6 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 7 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 8 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 9 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 10 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 11 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 12 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 13 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 14 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 15 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 16 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 17 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 18 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 19 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 20 | ERROR | SpeakableTextPresentCheck | android.widget.Button | This item may not have a label readable by screen readers. |
| 21 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 22 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 23 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 24 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 25 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 26 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 27 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 28 | ERROR | TouchTargetSizeCheck | android.widget.Button | This item's height is 18dp. Consider making the height of this touch target 48dp or larger. |
| 29 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Latest PR, Latest PR, Unavailable" is identical to that of 1 other item(s). |
| 30 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "come" is identical to that of 1 other item(s). |
| 31 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Open issues, Open issues, 2 issues" is identical to that of 1 other item(s). |
| 32 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Latest release, Latest release, V0.1.2" is identical to that of 1 other item(s). |
| 33 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "/" is identical to that of 2 other item(s). |
| 34 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Latest tag, Latest tag, V0.1.2" is identical to that of 1 other item(s). |
| 35 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "the" is identical to that of 5 other item(s). |
| 36 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "to" is identical to that of 1 other item(s). |
| 37 | WARNING | DuplicateSpeakableTextCheck | android.widget.Button | This clickable item's speakable text: "View on GitHub" is identical to that of 3 other item(s). |
| 38 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "from" is identical to that of 1 other item(s). |
| 39 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 3 other item(s). |
| 40 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "GitHub" is identical to that of 1 other item(s). |
| 41 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "no recent commit data" is identical to that of 3 other item(s). |
| 42 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Open PRs, Open PRs, 0 pull requests" is identical to that of 1 other item(s). |
| 43 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "badges" is identical to that of 1 other item(s). |
| 44 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "with" is identical to that of 1 other item(s). |
| 45 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "build" is identical to that of 1 other item(s). |
| 46 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "HA" is identical to that of 1 other item(s). |

### `DashboardViewMeshcoreControlsMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewMeshcoreControlsMobile_dashboard_meshcore_view_4_Controls_mobile-c76ed086.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |

### `DashboardViewMeshcoreOverviewMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewMeshcoreOverviewMobile_dashboard_meshcore_view_1_Overview_mobile-49f1bca6.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Last" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "·" is identical to that of 1 other item(s). |
| 7 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Contact, Contact, Stale" is identical to that of 1 other item(s). |

### `DashboardViewMeshcoreRoomServerMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewMeshcoreRoomServerMobile_dashboard_meshcore_view_3_Room_Server_mobi-76b5c26e.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 32dp. Consider making the height of this touch target 48dp or larger. |

### `DashboardViewMeshcoreSolarRepeaterMobile`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/DashboardViewMeshcoreSolarRepeaterMobile_dashboard_meshcore_view_2_Solar_Repeate-27a5d9ad.a11y.png" width="400" />

_No findings._

### `Dashboard_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Dashboard_Dark_dashboard_dark-a7939316.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 2 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 3 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 1 other item(s). |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen, On" is identical to that of 1 other item(s). |

### `Dashboard_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Dashboard_Light_dashboard_light-067cddba.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 2 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 3 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 1 other item(s). |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen, On" is identical to that of 1 other item(s). |

### `Entities_Availability_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entities_Availability_Dark_entities_availability_dark-63decfae.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 2 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 4 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 7 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 8 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 9 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 10 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 11 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 12 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 13 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 14 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Entities_Availability_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entities_Availability_Light_entities_availability_light-351a13c0.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 2 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 4 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 7 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 8 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 9 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 10 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 11 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 12 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 13 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 14 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Entities_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entities_Dark_entities_dark-ca9074ee.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Entities_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entities_Light_entities_light-c6e543b0.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Entities_Responsive_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entities_Responsive_Light_entities_responsive_narrow-07b32f2c.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `EntityFilter_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/EntityFilter_Dark_entity_filter_dark-9e0fdc38.a11y.png" width="400" />

_No findings._

### `EntityFilter_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/EntityFilter_Light_entity_filter_light-bc81e14a.a11y.png" width="400" />

_No findings._

### `Entity_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entity_Dark_entity_dark-9e9369db.a11y.png" width="400" />

_No findings._

### `Entity_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Entity_Light_entity_light-384a3a36.a11y.png" width="400" />

_No findings._

### `Glance_Availability_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Glance_Availability_Light_glance_availability_light-99a3b559.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 47dp. Consider making the width of this touch target 48dp or larger. |

### `Glance_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Glance_Dark_glance_dark-32fd9bc5.a11y.png" width="400" />

_No findings._

### `Glance_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Glance_Light_glance_light-90e59d6e.a11y.png" width="400" />

_No findings._

### `Glance_Responsive_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Glance_Responsive_Dark_glance_responsive_narrow-116d2469.a11y.png" width="400" />

_No findings._

### `Grid_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Grid_Dark_grid_dark-2c74835b.a11y.png" width="400" />

_No findings._

### `Grid_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Grid_Light_grid_light-ffbb7c50.a11y.png" width="400" />

_No findings._

### `HorizontalStack_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/HorizontalStack_Dark_horizontal_stack_dark-ff029033.a11y.png" width="400" />

_No findings._

### `HorizontalStack_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/HorizontalStack_Light_horizontal_stack_light-11d8599a.a11y.png" width="400" />

_No findings._

### `Logbook_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Logbook_Dark_logbook_dark-7e305fb6.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Garage motion" | This non-clickable item's speakable text: "Garage motion" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Front door" | This non-clickable item's speakable text: "Front door" is identical to that of 1 other item(s). |

### `Logbook_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Logbook_Light_logbook_light-b438574b.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Garage motion" | This non-clickable item's speakable text: "Garage motion" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Front door" | This non-clickable item's speakable text: "Front door" is identical to that of 1 other item(s). |

### `PictureElements_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/PictureElements_Dark_picture_elements_dark-5c619d18.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "element" is identical to that of 1 other item(s). |

### `PictureElements_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/PictureElements_Light_picture_elements_light-c5f77fdf.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "element" is identical to that of 1 other item(s). |

### `PictureGlance_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/PictureGlance_Dark_picture_glance_dark-26cfeaf0.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 4 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Living room" | This non-clickable item's speakable text: "Living room" is identical to that of 1 other item(s). |

### `PictureGlance_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/PictureGlance_Light_picture_glance_light-de890a08.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 3 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 40dp. Consider making the width of this touch target 48dp or larger. |
| 4 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Living room" | This non-clickable item's speakable text: "Living room" is identical to that of 1 other item(s). |

### `Sizing_ConstraintMatrix_PaintMeasure`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_ConstraintMatrix_PaintMeasure_sizing_width_height_matrix_paint_measure_pr-9f9b8e19.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 7 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 8 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 9 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 10 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 22dp. Consider making the height of this touch target 48dp or larger. |
| 11 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 3dp. Consider making the height of this touch target 48dp or larger. |
| 12 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 3dp. Consider making the height of this touch target 48dp or larger. |
| 13 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 8 other item(s). |
| 14 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "· w=380 × h=80 (clip) (host=380×80dp)" is identical to that of 1 other item(s). |
| 15 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Coffee maker, Coffee maker" is identical to that of 2 other item(s). |
| 16 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Living Room" is identical to that of 3 other item(s). |
| 17 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 2 other item(s). |

### `Sizing_ConstraintMatrix_Wrap`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_ConstraintMatrix_Wrap_sizing_width_height_matrix_wrap_profile-3a37721e.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 5 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 6 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 7 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 8 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 9 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 10 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 22dp. Consider making the height of this touch target 48dp or larger. |
| 11 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 3dp. Consider making the height of this touch target 48dp or larger. |
| 12 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 3dp. Consider making the height of this touch target 48dp or larger. |
| 13 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 8 other item(s). |
| 14 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "· w=380 × h=80 (clip) (host=380×80dp)" is identical to that of 1 other item(s). |
| 15 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Coffee maker, Coffee maker" is identical to that of 2 other item(s). |
| 16 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Living Room" is identical to that of 3 other item(s). |
| 17 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 2 other item(s). |

### `Sizing_FixedSlot_PaintMeasure`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_FixedSlot_PaintMeasure_sizing_fixed_slot_paint_measure_profile-78c4aec3.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 3 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_FixedSlot_Wrap`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_FixedSlot_Wrap_sizing_fixed_slot_wrap_profile-8dc35821.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 3 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_SlackSlot_PaintMeasure`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_SlackSlot_PaintMeasure_sizing_slack_slot_paint_measure_profile-2303bb70.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 3 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_SlackSlot_Wrap`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_SlackSlot_Wrap_sizing_slack_slot_wrap_profile-d620e6e1.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 3 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_TightSlot_PaintMeasure`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_TightSlot_PaintMeasure_sizing_tight_slot_paint_measure_profile-6d918ba0.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 2 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_TightSlot_Wrap`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_TightSlot_Wrap_sizing_tight_slot_wrap_profile-48f47102.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |
| 4 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 2 other item(s). |
| 5 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Kitchen, Kitchen" is identical to that of 1 other item(s). |

### `Sizing_WidthPinnedHeightAdaptive`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Sizing_WidthPinnedHeightAdaptive_sizing_width_pinned_height_adaptive-e082424e.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | WARNING | DuplicateSpeakableTextCheck | android.view.View | This clickable item's speakable text: "Living Room, Living Room, 21.4 °C" is identical to that of 1 other item(s). |

### `Theme_Home_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Home_Dark_theme_Home_dark-acc1d4cc.a11y.png" width="400" />

_No findings._

### `Theme_Home_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Home_Light_theme_Home_light-6ad707ff.a11y.png" width="400" />

_No findings._

### `Theme_Kiosk_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Kiosk_Dark_theme_Kiosk_dark-1117c554.a11y.png" width="400" />

_No findings._

### `Theme_Kiosk_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Kiosk_Light_theme_Kiosk_light-ccf401ed.a11y.png" width="400" />

_No findings._

### `Theme_Material3_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Material3_Dark_theme_Material3_dark-aa6413d9.a11y.png" width="400" />

_No findings._

### `Theme_Material3_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Material3_Light_theme_Material3_light-04be4799.a11y.png" width="400" />

_No findings._

### `Theme_Minimalist_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Minimalist_Dark_theme_Minimalist_dark-d6dfe091.a11y.png" width="400" />

_No findings._

### `Theme_Minimalist_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Minimalist_Light_theme_Minimalist_light-34a2c33e.a11y.png" width="400" />

_No findings._

### `Theme_Mushroom_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Mushroom_Dark_theme_Mushroom_dark-360b35ef.a11y.png" width="400" />

_No findings._

### `Theme_Mushroom_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Theme_Mushroom_Light_theme_Mushroom_light-70c4dd9a.a11y.png" width="400" />

_No findings._

### `Tile_Climate_Heating_Features`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Climate_Heating_Features_tile_climate_heating_features-b3865d14.a11y.png" width="400" />

_No findings._

### `Tile_Climate_Heating_Features_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Climate_Heating_Features_Dark_tile_climate_heating_features_dark-f1d1e8e2.a11y.png" width="400" />

_No findings._

### `Tile_Climate_Idle_Features`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Climate_Idle_Features_tile_climate_idle_features-6708b40c.a11y.png" width="400" />

_No findings._

### `Tile_Climate_Idle_Features_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Climate_Idle_Features_Dark_tile_climate_idle_features_dark-ac6cbf1e.a11y.png" width="400" />

_No findings._

### `Tile_Color_Blue`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Color_Blue_tile_colour_blue-b452d2ed.a11y.png" width="400" />

_No findings._

### `Tile_Color_Blue_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Color_Blue_Dark_tile_colour_blue_dark-d280dd42.a11y.png" width="400" />

_No findings._

### `Tile_Cover_States`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/ee.schimke.ha.previews.CardPreviewsKt.Tile_Cover_States_tile cover (light).a11y.png" width="400" />

_No findings._

### `Tile_Light_States`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/ee.schimke.ha.previews.CardPreviewsKt.Tile_Light_States_tile light (light).a11y.png" width="400" />

_No findings._

### `Tile_Lock_States`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/ee.schimke.ha.previews.CardPreviewsKt.Tile_Lock_States_tile lock (light).a11y.png" width="400" />

_No findings._

### `Tile_Responsive_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_Responsive_Dark_tile_responsive_narrow-2b116a2f.a11y.png" width="400" />

_No findings._

### `Tile_TemperatureSensor`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_TemperatureSensor_tile_sensor_temperature-f2f597a3.a11y.png" width="400" />

_No findings._

### `Tile_TemperatureSensor_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tile_TemperatureSensor_Dark_tile_sensor_temperature_dark-970dc699.a11y.png" width="400" />

_No findings._

### `Tiles_Availability_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tiles_Availability_Dark_tiles_availability_dark-c0e64dff.a11y.png" width="400" />

_No findings._

### `Tiles_Availability_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Tiles_Availability_Light_tiles_availability_light-052c5b12.a11y.png" width="400" />

_No findings._

### `Uber_Braun_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Braun_Dark_uber_Braun_dark-7d150a60.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Braun_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Braun_Light_uber_Braun_light-5a2c2283.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Classic_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Classic_Light_uber_Classic_light-42bf0d3f.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Console`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Console_uber_Console-e263c2ad.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Expressive_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Expressive_Dark_uber_Material_3_Expressive_dark-c2119956.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Expressive_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Expressive_Light_uber_Material_3_Expressive_light-900b0841.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Lcd_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Lcd_Dark_uber_LCD_Indiglo_backlight-7b414933.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Lcd_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Lcd_Light_uber_LCD_reflective-cb2651a0.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Nixie`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Nixie_uber_Nixie-89940734.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `Uber_Trinitron`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/Uber_Trinitron_uber_Trinitron-fa0b6c99.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 33dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. |
| 3 | WARNING | TouchTargetSizeCheck | android.view.View | This item's height is 34dp. Consider making the height of this touch target 48dp or larger. A parent container may be handling touch events for this item. If selecting the larger container performs the same action as selecting this item, consider defining this item as not clickable. If a different action is performed, consider increasing the size of this item. |

### `VerticalStack_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/VerticalStack_Dark_vertical_stack_dark-d359f199.a11y.png" width="400" />

_No findings._

### `VerticalStack_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/VerticalStack_Light_vertical_stack_light-f055bd90.a11y.png" width="400" />

_No findings._

### `WeatherForecast_Dark`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/WeatherForecast_Dark_weather_forecast_dark-eb2d793e.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Wind" | This non-clickable item's speakable text: "Wind" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sat" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Partlycloudy" | This non-clickable item's speakable text: "Partlycloudy" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Humidity" | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Thu" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Feels" | This non-clickable item's speakable text: "Feels" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sun" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Mon" is identical to that of 1 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Pressure" | This non-clickable item's speakable text: "Pressure" is identical to that of 1 other item(s). |
| 10 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Fri" is identical to that of 1 other item(s). |

### `WeatherForecast_Light`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/previews/WeatherForecast_Light_weather_forecast_light-36955f1d.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Wind" | This non-clickable item's speakable text: "Wind" is identical to that of 1 other item(s). |
| 2 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sat" is identical to that of 1 other item(s). |
| 3 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Partlycloudy" | This non-clickable item's speakable text: "Partlycloudy" is identical to that of 1 other item(s). |
| 4 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Humidity" | This non-clickable item's speakable text: "Humidity" is identical to that of 1 other item(s). |
| 5 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Thu" is identical to that of 1 other item(s). |
| 6 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Feels" | This non-clickable item's speakable text: "Feels" is identical to that of 1 other item(s). |
| 7 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Sun" is identical to that of 1 other item(s). |
| 8 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Mon" is identical to that of 1 other item(s). |
| 9 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Pressure" | This non-clickable item's speakable text: "Pressure" is identical to that of 1 other item(s). |
| 10 | INFO | DuplicateSpeakableTextCheck | android.widget.TextView | This non-clickable item's speakable text: "Fri" is identical to that of 1 other item(s). |

## wear

### `SlotWidgetPreview_EntitiesLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/SlotWidgetPreview_EntitiesLarge_Slot_widget_entities_large-2795b182.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 46dp. Consider making the height of this touch target 48dp or larger. |

### `SlotWidgetPreview_TileSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/SlotWidgetPreview_TileSmall_Slot_widget_tile_small-926c14a3.a11y.png" width="400" />

_No findings._

### `WearEntitiesLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearEntitiesLarge_wear_entities_large-514ab5ad.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 30dp. Consider making the height of this touch target 48dp or larger. |
| 2 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 30dp. Consider making the height of this touch target 48dp or larger. |

### `WearEntitiesSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearEntitiesSmall_wear_entities_small-e89438b8.a11y.png" width="400" />

_No findings._

### `WearEntityFilterLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearEntityFilterLarge_wear_entity_filter_large-ced2911f.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 46dp. Consider making the width of this touch target 48dp or larger. |

### `WearEntityLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearEntityLarge_wear_entity_large-418b2856.a11y.png" width="400" />

_No findings._

### `WearEntitySmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearEntitySmall_wear_entity_small-67223bdb.a11y.png" width="400" />

_No findings._

### `WearGlanceLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearGlanceLarge_wear_glance_large-611befa6.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's width is 46dp. Consider making the width of this touch target 48dp or larger. |

### `WearLogbookSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearLogbookSmall_wear_logbook_small-95be0862.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Front door" | This non-clickable item's speakable text: "Front door" is identical to that of 1 other item(s). |

### `WearTileLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearTileLarge_wear_tile_large-b7bc3df3.a11y.png" width="400" />

_No findings._

### `WearTileSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearTileSmall_wear_tile_small-b9346ba9.a11y.png" width="400" />

_No findings._

### `WearVerticalStackLarge`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearVerticalStackLarge_wear_vertical_stack_large-6822a2ac.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | ERROR | TouchTargetSizeCheck | android.view.View | This item's height is 8dp. Consider making the height of this touch target 48dp or larger. |

### `WearVerticalStackSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearVerticalStackSmall_wear_vertical_stack_small-8329a953.a11y.png" width="400" />

_No findings._

### `WearWeatherForecastSmall`

<img src="https://raw.githubusercontent.com/yschimke/homeassistant-remotecompose-out/compose-preview/a11y/pr/renders/wear/WearWeatherForecastSmall_wear_weather_forecast_small-95a921f7.a11y.png" width="400" />

| # | Level | Rule | Element | Message |
|--:|---|---|---|---|
| 1 | INFO | DuplicateSpeakableTextCheck | android.view.View  desc="Partlycloudy" | This non-clickable item's speakable text: "Partlycloudy" is identical to that of 1 other item(s). |
