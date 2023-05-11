
<h1 align="center">🫡  I'm XieWei </h1>
<h3 align="center">A software developer </h3>



## 💬 Talk with me
- Backend web development (go、rust、python)
- Cool idea about production


## 🫡 Find me
[Wechat](javascript:void(0))

<div id="modal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>🫡 Scan Me!</p>
    <img src="./img/wechat.jpg" alt="wu_xiaoshen">
  </div>
</div>

<style>
/* 模态框 */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0,0,0,0.8);
}

/* 模态框内容 */
.modal-content {
  position: relative;
  background-color: #fefefe;
  margin: auto;
  padding: 20px;
  border: 1px solid #888;
  width: 80%;
  max-width: 600px;
}

/* 关闭按钮 */
.close {
  position: absolute;
  top: 0;
  right: 0;
  color: #aaa;
  font-size: 28px;
  font-weight: bold;
  cursor: pointer;
}

/* 当鼠标悬停在关闭按钮上时，改变样式 */
.close:hover,
.close:focus {
  color: black;
  text-decoration: none;
  cursor: pointer;
}
</style>

<script>
// 获取模态框和关闭按钮
var modal = document.getElementById("modal");
var close = document.getElementsByClassName("close")[0];

// 点击链接时弹出模态框
document.querySelector('a[href="javascript:void(0)"]').onclick = function() {
  modal.style.display = "block";
}

// 点击关闭按钮或模态框外部时关闭模态框
close.onclick = function() {
  modal.style.display = "none";
}

window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>