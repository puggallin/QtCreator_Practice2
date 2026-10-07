<?xml version="1.0" encoding="UTF-8"?>
<ui version="4.0">
 <class>MainWindow</class>
 <widget class="QMainWindow" name="MainWindow">
  <property name="geometry">
   <rect>
    <x>0</x>
    <y>0</y>
    <width>1100</width>
    <height>480</height>
   </rect>
  </property>
  <property name="windowTitle">
   <string>Мониторинг парка БПЛА</string>
  </property>
  <widget class="QWidget" name="centralwidget">
   <layout class="QHBoxLayout" name="mainLayout">
    <item>
     <widget class="QGraphicsView" name="graphicsView">
      <property name="minimumSize">
       <size>
        <width>620</width>
        <height>420</height>
       </size>
      </property>
     </widget>
    </item>
    <item>
     <layout class="QVBoxLayout" name="rightLayout">
      <item>
       <widget class="QTableWidget" name="tableWidget">
        <property name="minimumSize">
         <size>
          <width>420</width>
          <height>0</height>
         </size>
        </property>
       </widget>
      </item>
      <item>
       <widget class="QLabel" name="labelUpdated">
        <property name="text">
         <string>Обновлено: </string>
        </property>
       </widget>
      </item>
      <item>
       <layout class="QHBoxLayout" name="buttonsLayout">
        <item>
         <widget class="QPushButton" name="btnPause">
          <property name="text">
           <string>Пауза</string>
          </property>
         </widget>
        </item>
        <item>
         <widget class="QPushButton" name="btnReset">
          <property name="text">
           <string>Сброс</string>
          </property>
         </widget>
        </item>
       </layout>
      </item>
     </layout>
    </item>
   </layout>
  </widget>
 </widget>
 <resources/>
 <connections/>
</ui>
