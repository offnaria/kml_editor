# KML Map Viewer

## English

### Overview
KML Map Viewer is a web-based application for viewing, editing, and exporting KML (Keyhole Markup Language) files. It provides an interactive interface to visualize geographic data stored in KML format on a map.

### Features
- **KML File Loading**: Load KML files via file input or drag-and-drop
- **Interactive Map Display**: View KML features on an OpenStreetMap background
- **Feature Organization**: View layers and features in an organized sidebar
- **Feature Styling**:
  - Change colors of lines and polygons with a color picker
  - Colors are preserved when exporting KML files
- **Feature Manipulation**:
  - Displace features by precise latitude and longitude values
  - Use keyboard shortcuts for fine-tuning the displacement
- **Feature Navigation**:
  - Center the map on specific features
  - Toggle feature visibility
- **KML Export**: Export the modified KML data back to a KML file

### How to Use
1. **Loading KML Files**: 
   - Click "Choose File" and select a KML file, then click "Load KML"
   - Or drag and drop a KML file onto the map area

2. **Viewing Features**:
   - The sidebar on the left shows layers and features from the KML file
   - Click on a feature to center the map on it

3. **Editing Features**:
   - **Changing Colors**: For lines and polygons, use the color picker to change colors
   - **Displacing Features**: Click the "Displace" button next to a feature to move it
     - Enter latitude/longitude shift values or use arrow keys
     - Hold Shift with arrow keys for larger movements
     - Press Enter to apply or Escape to cancel

4. **Managing Visibility**:
   - Click the eye icon (👁️) next to a feature to toggle its visibility

5. **Exporting KML**:
   - Click "Export KML" to save your changes as a new KML file

### Keyboard Shortcuts
- **Arrow Keys**: When in displacement mode, move the feature
- **Shift + Arrow Keys**: Larger displacement steps
- **Enter**: Apply displacement
- **Escape**: Cancel displacement

## 日本語

### 概要
KML Map Viewerは、KML（Keyhole Markup Language）ファイルを表示、編集、エクスポートするためのWeb アプリケーションです。KML形式で保存された地理データを地図上でインタラクティブに表示できます。

### 機能
- **KMLファイルの読み込み**: ファイル入力またはドラッグ＆ドロップでKMLファイルを読み込み
- **インタラクティブな地図表示**: OpenStreetMap上でKML要素を表示
- **要素の整理**: サイドバーでレイヤーや要素を整理して表示
- **要素のスタイル変更**:
  - カラーピッカーでラインやポリゴンの色を変更
  - エクスポート時に色が保持される
- **要素の操作**:
  - 緯度・経度の値で要素を正確に移動
  - キーボードショートカットで微調整が可能
- **要素のナビゲーション**:
  - 特定の要素に地図を中心化
  - 要素の表示/非表示を切り替え
- **KMLエクスポート**: 変更したKMLデータをKMLファイルとしてエクスポート

### 使用方法
1. **KMLファイルの読み込み**: 
   - 「ファイルを選択」をクリックしてKMLファイルを選び、「KMLを読み込む」をクリック
   - または地図エリアにKMLファイルをドラッグ＆ドロップ

2. **要素の表示**:
   - 左側のサイドバーにKMLファイルのレイヤーと要素が表示される
   - 要素をクリックすると地図の中心がその要素に移動

3. **要素の編集**:
   - **色の変更**: ラインやポリゴンの場合、カラーピッカーで色を変更可能
   - **要素の移動**: 要素の横にある「Displace」ボタンをクリックして移動
     - 緯度/経度のシフト値を入力するか矢印キーで移動
     - 大きく移動するにはShiftキーを押しながら矢印キーを使用
     - 適用するにはEnterキー、キャンセルするにはEscapeキーを押す

4. **表示の管理**:
   - 要素の横にある目のアイコン（👁️）をクリックすると表示/非表示を切り替え

5. **KMLのエクスポート**:
   - 「Export KML」をクリックすると変更をKMLファイルとして保存

### キーボードショートカット
- **矢印キー**: 移動モードで要素を移動
- **Shift + 矢印キー**: 大きい移動ステップ
- **Enter**: 移動を適用
- **Escape**: 移動をキャンセル