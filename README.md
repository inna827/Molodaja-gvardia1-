# Molodaja-gvardia1-
import time
import random
import sys # Для sys.exit() и sys.stdout.write

# --- Глобальные переменные для состояния игры ---
player_name = ""
player_gender = ""
player_path = "neutral" # 'resistance', 'survival', 'forced_resistance', 'betrayal'
inventory = [] # Хранит объекты Item
player_stats = {
    'courage': 5,      # Смелость, влияет на бой и рискованные действия
    'stealth': 5,      # Скрытность, влияет на незаметность
    'ingenuity': 5,    # Изобретательность, влияет на обман, отвлечение
    'loyalty_resistance': 50, # От 0 до 100, влияет на доверие Молодой Гвардии и их отношение
    'loyalty_enemy': 0,      # От 0 до 100, влияет на доверие немцев и их отношение
    'health': 100,     # Здоровье
    'ammo_pistol': 0   # Количество патронов для пистолета
}



О молодежной организации
