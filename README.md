Plots. Python tutorials. Jupyter Notebook. Math. XYPlots.
To create a Jupyter notebook, follow these steps:
  1. Launch terminal.
  2. Select the location to create the Jupyter notebook (use the cd, mkdir commands).
  3. Type "jupyter notebook" in it.
  4. The browser with the Jupyter system web interface will launch.
  5. Click the "New" button and select "Python3 (pykernel)" from the drop-down menu.
  6. Click the "Add" button (the "+" sign) on the toolbar to create 2 more cells.
  7. In cell #1, enter the code:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-4,4,0.1)
     y = x ** 2 
     plt.plot(y)
  8. In cell №2, enter the code:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-4,4,0.1)
     y = x
     plt.plot(y)
  9. In cell #3, enter the code:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-10, -0.5, 0.1)
     y = 1 / x
     plt.plot(y)
     x = np.arange(0.5, 10, 0.1)
     y = 1 / x
     plt.plot(y)
  10. Click the "Run" button (black arrow) on the toolbar.

HelloWorld. Занятия Python. Блокноты Jupyter. Математика. Двухмерные графики функций.
Для создания блокнота Jupyter нужно выполнить следующие действия:
  1. Запустить терминал.
  2. Выбрать место создания блокнота "Jupyter" (использовать комманды cd,mkdir).
  3. В нём набрать "jupyter notebook".
  4. Запустится браузер с веб интерфейсом системы "Jupyter".
  5. Нажать кнопку "New" и выпадающем меню выбрать пункт "Python3 (pykernel)".
  6. Нажать кнопку "Добавить" (знак "+") на панели инструментов для создания ещё 2 ячеек.
  7. В ячейке № 1 ввести код:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-4,4,0.1)
     y = x ** 2 
     plt.plot(y)
  8. В ячейке № 2 ввести код:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-4,4,0.1)
     y = x
     plt.plot(y)
  9. В ячейке № 3 ввести код:
     import matplotlib.pyplot as plt
     import numpy as np
     x = np.arange(-10, -0.5, 0.1)
     y = 1 / x
     plt.plot(y)
     x = np.arange(0.5, 10, 0.1)
     y = 1 / x
     plt.plot(y)
  10. Нажать кнопку "Выполнить" (чёрная стрелка) на панели инструментов.
