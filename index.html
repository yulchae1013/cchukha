<!DOCTYPE html>
<html>
<head>
  <title>산들 1-3</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      width: 100px;
      height: 150px;
      background-color: lightgray;
      border: 1px solid gray;
      display: inline-block;
      margin: 5px;
      text-align: center;
      vertical-align: middle;
      line-height: 150px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .card.clicked {
      background-color: white;
    }
  </style>
</head>
<body>
  <label for="numCards">숫자:</label>
  <input type="number" id="numCards" min="1" value="1">
  <button onclick="drawCards()">자리뽑기</button>
  <div id="cardContainer"></div>

  <script>
    var names = [
      "고은혜", "고현우", "권예솔", "김선우", "김승현", "김예인", "김혜중", "김태훈",
      "남가현", "조동현", "명시하", "반우영", "김서율", "송영은", "송하운", "엄승리",
      "정연우", "유원희", "윤정한", "석지민", "이예지", "이윤지", "이현서", "임지현",
      "최환이", "유하은", "한윤성", "서현우", "이서진", "진홍명", "조은주", "황재윤",
      "원준호", "이채율", "형지나"
    ];
    var availableNames = names.slice(); // Copy the array of names

    function drawCards() {
      var numCardsInput = document.getElementById("numCards");
      var numCards = parseInt(numCardsInput.value, 10);

      var cardContainer = document.getElementById("cardContainer");
      cardContainer.innerHTML = ""; // Clear previous cards

      var numPerRow = 6;
      var numRows = Math.ceil(numCards / numPerRow);

      for (var i = 0; i < numRows; i++) {
        var rowDiv = document.createElement("div");
        rowDiv.className = "row";

        for (var j = 0; j < numPerRow; j++) {
          if (numCards <= 0) {
            break; // Break if no more cards are left
          }

          var cardDiv = document.createElement("div");
          cardDiv.className = "card";
          cardDiv.textContent = "카드";
          cardDiv.addEventListener("click", function() {
            changeCardText(this);
          });
          rowDiv.appendChild(cardDiv);

          numCards--;
        }

        cardContainer.appendChild(rowDiv);
      }
    }

    function changeCardText(cardElement) {
      if (availableNames.length === 0) {
        cardElement.textContent = "더 이상 이름 없음";
        return;
      }

      var randomIndex = Math.floor(Math.random() * availableNames.length);
      var selectedName = availableNames.splice(randomIndex, 1)[0];
      cardElement.textContent = selectedName;
      cardElement.classList.add("clicked");
    }
  </script>
</body>
</html>
