## Как запустить код на кластере?

В корневой папке проекта выполнить команду

		sbatch -n 20 -D ./results ./run.sh 

-n - количество ядер
-D - директория для сохранения результатов

