<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Энциклопедия RP терминов</title>
    <style>
        :root {
            --primary-color: #4caf50;
            --secondary-color: #2e7d32;
            --light-accent: #81c784;
            --dark-bg: #121212;
            --card-bg: #1e1e1e;
            --header-bg: #1a1a1a;
            --text-color: #e0e0e0;
        }
        
        * {
            box-sizing: border-box;
        }
        
        body {
            background-color: var(--dark-bg);
            color: var(--text-color);
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            font-size: 16px;
            -webkit-text-size-adjust: 100%;
        }
        
        header {
            background-color: var(--header-bg);
            padding: 15px;
            text-align: center;
            border-bottom: 3px solid var(--secondary-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        h1 {
            color: var(--primary-color);
            margin: 0;
            font-size: 1.8rem;
        }
        
        .container {
            width: 100%;
            padding: 10px;
        }
        
        .term-card {
            background-color: var(--card-bg);
            border-left: 4px solid var(--secondary-color);
            padding: 12px;
            margin-bottom: 15px;
            border-radius: 0 5px 5px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.3);
        }
        
        .term-title {
            color: var(--primary-color);
            font-size: 1.3rem;
            margin-top: 0;
            margin-bottom: 8px;
            word-break: break-word;
        }
        
        .term-abbreviation {
            color: var(--light-accent);
            font-weight: bold;
            font-size: 0.95rem;
        }
        
        .term-description {
            margin-top: 8px;
            font-size: 0.95rem;
        }
        
        footer {
            background-color: var(--header-bg);
            padding: 12px;
            text-align: center;
            border-top: 3px solid var(--secondary-color);
            margin-top: 20px;
            font-size: 0.9rem;
        }
        
        .search-box {
            margin: 15px 0;
            padding: 0 5px;
        }
        
        #search {
            padding: 10px;
            width: 100%;
            max-width: 400px;
            background-color: #2d2d2d;
            border: 1px solid var(--secondary-color);
            color: var(--text-color);
            border-radius: 4px;
            font-size: 1rem;
            margin: 0 auto;
            display: block;
        }
        
        .category {
            color: var(--light-accent);
            font-weight: bold;
            margin-top: 25px;
            border-bottom: 1px solid var(--secondary-color);
            padding-bottom: 5px;
            font-size: 1.2rem;
            padding-left: 5px;
        }
        
        /* Улучшение для маленьких экранов */
        @media (max-width: 480px) {
            .term-card {
                padding: 10px;
            }
            
            .term-title {
                font-size: 1.2rem;
            }
            
            h1 {
                font-size: 1.5rem;
            }
        }
        
        /* Анимация для плавного появления карточек */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .term-card {
            animation: fadeIn 0.3s ease-out forwards;
            opacity: 0;
        }
        
        /* Задержка для анимации */
        .term-card:nth-child(1) { animation-delay: 0.1s; }
        .term-card:nth-child(2) { animation-delay: 0.15s; }
        .term-card:nth-child(3) { animation-delay: 0.2s; }
        .term-card:nth-child(4) { animation-delay: 0.25s; }
        .term-card:nth-child(5) { animation-delay: 0.3s; }
        .term-card:nth-child(6) { animation-delay: 0.35s; }
        .term-card:nth-child(7) { animation-delay: 0.4s; }
        .term-card:nth-child(8) { animation-delay: 0.45s; }
        .term-card:nth-child(9) { animation-delay: 0.5s; }
        .term-card:nth-child(10) { animation-delay: 0.55s; }
        /* и так далее... */
    </style>
</head>
<body>
    <header>
        <h1>Энциклопедия RP терминов</h1>
    </header>
    
    <div class="container">
        <div class="search-box">
            <input type="text" id="search" placeholder="Поиск терминов..." autocapitalize="off" autocomplete="off">
        </div>
        
        <div class="term-card">
            <h3 class="term-title">РП (RP)</h3>
            <div class="term-abbreviation">Role Play - Игра по ролям</div>
            <div class="term-description">Игра по ролям где каждый должен соблюдать свою роль.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">IC</h3>
            <div class="term-abbreviation">In Character - «В роли своего персонажа»</div>
            <div class="term-description">Внутриигровая информация и действия.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ООС</h3>
            <div class="term-abbreviation">Out Of Character - «За ролью персонажа»</div>
            <div class="term-description">Информация и действия, никак не касающиеся игры на RP проекте.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ДМ (DM)</h3>
            <div class="term-abbreviation">Deathmatch</div>
            <div class="term-description">Убийство или нанесение урона без причины.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ДБ (DB)</h3>
            <div class="term-abbreviation">DriveBy</div>
            <div class="term-description">Убийство или нанесение урона с машины (машиной).</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">CK (SK)</h3>
            <div class="term-abbreviation">SpawnKill</div>
            <div class="term-description">Спавн килл, т.е. убийство или нанесение урона при появлении.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ТК (TK)</h3>
            <div class="term-abbreviation">TeamKill</div>
            <div class="term-description">Убийство или нанесение урона своим.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">МГ (MG)</h3>
            <div class="term-abbreviation">MetaGaming</div>
            <div class="term-description">Использование информации из реального мира в игровой чат (сокращенно: ООС в IC).</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ГM (GM)</h3>
            <div class="term-abbreviation">GodMode</div>
            <div class="term-description">Бог мод - т.е. режим бога.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ПГ (PG)</h3>
            <div class="term-abbreviation">PowerGaming</div>
            <div class="term-description">Изображение из себя героя, например когда у тебя нет оружия и ты идешь на человека у которого оно есть, или например драка 5 против одного.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">PK (RK)</h3>
            <div class="term-abbreviation">RevengKill</div>
            <div class="term-description">
                1. Возвращение на место где тебя убили.<br>
                2. Убийство с целью мести.<br>
                3. Неоднократное намеренное убийство одного и того же игрока.
            </div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">БХ (ВХ)</h3>
            <div class="term-abbreviation">BunnyHop</div>
            <div class="term-description">"Бани Хоп" - нонРП бег с прыжками (shift+space).</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ФР (FR)</h3>
            <div class="term-abbreviation">FastReloading</div>
            <div class="term-description">Баг с быстрой перезарядкой.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ФМ (FM)</h3>
            <div class="term-abbreviation">FastMoving</div>
            <div class="term-description">Баг с быстрым перемещением.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">CX (SH)</h3>
            <div class="term-abbreviation">SpeedHack</div>
            <div class="term-description">Спидхак, чит на быстрое перемещение.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ТП (ТР)</h3>
            <div class="term-abbreviation">Teleport</div>
            <div class="term-description">Телепорт.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ФФ (FF)</h3>
            <div class="term-abbreviation">Friendly Fire</div>
            <div class="term-description">Стрельба по своим. К примеру по друзьям, не убивая их а оставляя к примеру 10хп, стрельба в шутку.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ЦК</h3>
            <div class="term-description">Убийство по рп, запрещено на сервере.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ЕПП</h3>
            <div class="term-description">Езда по полям.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ОРП</h3>
            <div class="term-description">Уход от РП.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ТДМ</h3>
            <div class="term-description">Массовое ДМ.</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">УК (YК)</h3>
            <div class="term-description">"Уголовный Кодекс"</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">АК (АK)</h3>
            <div class="term-description">"Академический Кодекс"</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">33 (GZ)</h3>
            <div class="term-abbreviation">GreenZone</div>
            <div class="term-description">"Зеленая Зона". Общественные места-площадь у мэрии, вокзалы, больницы и т.п. (В этой зоне запрещено стрелять).</div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ПК</h3>
            <div class="term-abbreviation">Player Kill - смерть игрока</div>
            <div class="term-description">
                Случайная смерть игрока от каких либо моментов. Не наносит урона персонажу, тем самым давая возможность продолжать RP за него. 
                Считается как тяжкая/ряд мелких ран, давшая/ые герою краткую амнезию, болевой шок и потерю сознания.
            </div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">FearRP</h3>
            <div class="term-abbreviation">Fear - страх</div>
            <div class="term-description">
                При FearRP ваш персонаж должен боятся смерти, что происходит и в реальном мире.
            </div>
        </div>
        
        <div class="term-card">
            <h3 class="term-title">ФЦК</h3>
            <div class="term-description">Фракционное убийство.</div>
        </div>
    </div>
    
    <footer>
        <p>неблагодорите но если хотите тг @MrrDanya</p>
    </footer>
    
    <script>
        // Улучшенный поиск по терминам с задержкой
        let searchTimeout;
        document.getElementById('search').addEventListener('input', function() {
            clearTimeout(searchTimeout);
            searchTimeout = setTimeout(() => {
                const searchTerm = this.value.trim().toLowerCase();
                const termCards = document.querySelectorAll('.term-card');
                
                termCards.forEach(card => {
                    const text = card.textContent.toLowerCase();
                    if (searchTerm === '' || text.includes(searchTerm)) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            }, 200);
        });
        
        // Плавное отображение карточек при загрузке
        document.addEventListener('DOMContentLoaded', () => {
            const cards = document.querySelectorAll('.term-card');
            cards.forEach((card, index) => {
                card.style.animationDelay = `${0.1 + index * 0.05}s`;
            });
        });
    </script>
</body>