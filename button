import sys
from PyQt5.QtCore import Qt
from PyQt5.QtWidgets import QApplication, QWidget, QLabel, QHBoxLayout, QVBoxLayout, QRadioButton, QButtonGroup, QPushButton,QMessageBox
from PyQt5.QtGui import QFont

#Создаем скелет приложения
app = QApplication([])
my_win = QWidget()
my_win.setWindowTitle('Языки программирования')
my_win.resize(400, 300)
v_line = QVBoxLayout()

#Создаю радиокнопки
btn_answer1 = QRadioButton('1')
btn_answer2 = QRadioButton('2')
btn_answer3 = QRadioButton('3')
btn_answer1.setChecked(True)

#Создаю группу радиокнопок
button_group = QButtonGroup()
button_group.addButton(btn_answer1, id=1)
button_group.addButton(btn_answer2, id=2)
button_group.addButton(btn_answer3, id=3)

#Размещаю радиокнопки
v_line.addWidget(btn_answer1, alignment= Qt.AlignLeft)
v_line.addWidget(btn_answer2, alignment= Qt.AlignLeft)
v_line.addWidget(btn_answer3, alignment= Qt.AlignLeft)



#Функция для батона
def but():
    line.setText('Выбрана кнопка под номером ' + str(button_group.checkedId()))




#Создаю кнопку
button = QPushButton('Проверить')
v_line.addWidget(button, alignment= Qt.AlignCenter)
button.clicked.connect(but)


#Создаю текст
line = QLabel('')
v_line.addWidget(line, alignment = Qt.AlignCenter)
line.setText('Выбрана кнопка под номером ' + str(button_group.checkedId()))





my_win.setLayout(v_line)
my_win.show()
app.exec_()
