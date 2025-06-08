---
author: linh_dang
title: "Cơ Thể Bạn Đã Sẵn Sàng Cho Sinh Thường Chưa?"
collection: blogs
permalink: /blogs/co-the-ban-da-san-sang-cho-sinh-thuong-chua/
excerpt_separator: "<!--more-->"
---

<!-- markdownlint-disable MD028 -->
<!-- markdownlint-disable MD033 -->

<div class="quiz-container">
  <!-- Progress Bar -->
  <div class="progress-container">
    <div class="progress-bar">
      <div class="progress-fill" id="progressFill"></div>
    </div>
    <div class="progress-text" id="progressText"></div>
  </div>

  <!-- Dynamic Question Container -->
  <div id="questionContainer"></div>

  <!-- Results Section -->
  <div class="quiz-results" id="results" style="display: none;">
    <h3>Quiz Complete!</h3>
    <div id="finalScore"></div>
    <button type="button" onclick="retryQuiz()" class="retry-btn">Retry Quiz</button>
  </div>
</div>

{% include quiz_utils.html %}
