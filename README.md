# AulaRelativeLayout

## Center In Parent
Centraliza o elemento no centro da tela
```
android:layout_centerInParent="true"
```
## Center Horizontal
Centraliza elemento Horizontalmente
```
android:layout_centerHorizontal="true"
```
## Center Vertical
Centraliza elemento Verticalmente
```
android:layout_centerVertical="true"
```
## Align Parent Right
Alinhar elemento à direita do Container "RelativeLayout"
```
android:layout_alignParentRight="true"
```
## Align Parent Bottom
Alinhar elemento no Bottom do Container "RelativeLayout"
```
android:layout_alignParentBottom="true"
```
## Align To Right Of
Alinhar elemento à direita de outro elemento, neste exemplo chamado b1
```
android:layout_toRightOf="@id/b1"
```
## Align To Left Of
Alinhar elemento à esquerda de outro elemento, neste exemplo chamado b1
```
android:layout_toLeftOf="@id/b1"
```
## Below
Alinhar elemento abaixo de outro elemento, neste exemplo chamado b1
```
android:layout_below="@id/b1"
```
## Above
Alinhar elemento acima de outro elemento, neste exemplo chamado b1
```
android:layout_above="@id/b1"
```
## Fazer um botão redondo
Criar um arquivo no drawable
```xml
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android">

    <solid android:color="@color/purple_500" />
    <corners android:radius="25dp"/>

</shape>
```
