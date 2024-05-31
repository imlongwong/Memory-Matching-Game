<!DOCTYPE html>
<html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"> 
	
    <title>動態可點擊網格</title> 

    <style>
        * {
            font-family: Arial; 
        }

        header, footer {
            background-color: #666666; 
            color: #FFFFFF; 
            text-align: center; 
            padding: 10px; 
        }

        main {
            padding: 10px 0; 
        }

        .grid-container {
            display: grid; 
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 10px; 
            width: 240px;
            margin: auto; 
        }

        .grid-item {
            display: grid; 
            width: 80px; 
            height: 80px; 
            justify-content: center; 
            align-items: center; 
            background-color: #F0F0F0; 
            cursor: pointer;
            
            font-size: 60px;
            text-indent: 1000px;
            overflow: hidden;
        }

        .yellow {
            text-indent: 0px ;
        }
        
        .green {
            background-color: #0f0; 
        }
    </style>
</head>

<body>

<header>
	<h1>動態可點擊網格</h1> 
</header>

<main>
    <div class="grid-container" id="grid-container">
    </div>
</main>

<footer>
    <b>單元五練習三</b> 
</footer>

<script>
 const emoji =['☺️','😌','😁','😏','😔','😂','😭','😳'];
 const cards = [...emoji, ...emoji];
	function toggleGridSelection(event) {
		var grid = event.target; 
		var clickCount = grid.getAttribute('data-click-count') || 0;
		
		clickCount = parseInt(clickCount, 10);
		grid.classList.remove('yellow','green');
		
		switch (clickCount) {
			case 0:
				grid.classList.add('yellow');
				break;
			case 1:
				clickCount = -1;
				break;
		}
	
		clickCount += 1;	
		grid.setAttribute('data-click-count', clickCount.toString());
	}
	
	const gridSize = 4; // prompt('請輸入網格尺寸（例如：3 表示 3x3 網格）:');
	const gridContainer = document.getElementById('grid-container');
  	gridContainer.style.gridTemplateColumns = `repeat(${gridSize}, 1fr)`;
	gridContainer.style.width = `${gridSize * 80 + (gridSize - 1) * 10}px`;
        
	for (let i = 1; i <= gridSize * gridSize; i++) {
		const gridItem = document.createElement('div');
		gridItem.className = 'grid-item';
		gridItem.textContent = cards[i-1];
		gridContainer.appendChild(gridItem);
	}
        
	document.querySelectorAll('.grid-item').forEach(function (grid) {
		grid.addEventListener('click', toggleGridSelection);
	});
</script>

</body>
</html>
