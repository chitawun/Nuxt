<template>
    <div class="container mt-5">
      <!-- ขนาด -->
      <div class="mb-4">
        <h5>ขนาด</h5>
        <div class="btn-group" role="group" aria-label="Size options">
          <input type="radio" class="btn-check" name="sizeOptions" id="sizeVertical" autocomplete="off" />
          <label class="btn btn-outline-primary" for="sizeVertical">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-tablet" viewBox="0 0 16 16">
              <path d="M12 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1zM4 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2z" />
              <path d="M8 14a1 1 0 1 0 0-2 1 1 0 0 0 0 2" />
            </svg>
            แนวตั้ง
          </label>
  
          <input type="radio" class="btn-check" name="sizeOptions" id="sizeHorizontal" autocomplete="off" />
          <label class="btn btn-outline-primary" for="sizeHorizontal">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-tablet-landscape" viewBox="0 0 16 16">
              <path d="M1 4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1zm-1 8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2z" />
              <path d="M14 8a1 1 0 1 0-2 0 1 1 0 0 0 2 0" />
            </svg>
            แนวนอน
          </label>
  
          <input type="radio" class="btn-check" name="sizeOptions" id="sizeSquare" autocomplete="off" />
          <label class="btn btn-outline-primary" for="sizeSquare">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-square me-2" viewBox="0 0 16 16">
              <path d="M14 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1zM2 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2z" />
            </svg>
            จัตุรัส
          </label>
        </div>
      </div>
  
      <!-- หมวดหมู่ -->
      <div class="mb-4">
        <h5>หมวดหมู่</h5>
        <div class="row">
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">การงาน</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">การเงิน</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">ความรัก</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">สุขภาพ</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">ความมั่นใจ</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">ความสำเร็จ</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">เวลา</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">ศีลธรรม</button>
          </div>
          <div class="col-6 col-md-4">
            <button type="button" class="btn btn-outline-secondary w-100 mb-2">ความหวัง</button>
          </div>
        </div>
      </div>
  
      <!-- สไตล์ภาพ -->
      <div class="mb-4">
        <h5>สไตล์ภาพ</h5>
        <div class="row row-cols-2 row-cols-md-4 g-3">
          <div class="col">
            <div class="text-center">
              <img src="https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png" width="100" height="100" class="img-thumbnail mb-2" alt="Vintage" />
              <p class="text-center">Vintage</p>
            </div>
          </div>
          <div class="col">
            <div class="text-center">
              <img src="https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png" width="100" height="100" class="img-thumbnail mb-2" alt="Modern" />
              <p class="text-center">Modern</p>
            </div>
          </div>
          <div class="col">
            <div class="text-center">
              <img src="https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png" width="100" height="100" class="img-thumbnail mb-2" alt="Romantic" />
              <p class="text-center">Romantic</p>
            </div>
          </div>
          <div class="col">
            <div class="text-center">
              <img src="https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png" width="100" height="100" class="img-thumbnail mb-2" alt="Anime" />
              <p class="text-center">Anime</p>
            </div>
          </div>
        </div>
      </div>
  
      <!-- ลิงก์โหลดเพิ่ม -->
      <div class="text-center mt-4">
        <button class="btn btn-primary" @click="showMoreStyles">โหลดเพิ่ม</button>
      </div>
    </div>
  </template>
  
  <script setup>
  function showMoreStyles() {
    const newStyles = `
    <div class='col'>
      <div class='text-center'>
        <img src='https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png' width='100' height='100' class='img-thumbnail mb-2' alt='Anime Style 1'>
      </div>
    </div>
    <div class='col'>
      <div class='text-center'>
        <img src='https://e1.pngegg.com/pngimages/700/744/png-clipart-anime-render-001-green-long-hair-female-cartoon-character-in-red-dress.png' width='100' height='100' class='img-thumbnail mb-2' alt='Anime Style 2'>
      </div>
    </div>
    <div class='col'>
      <div class='text-center'>
        <img src='https://e1.pngegg.com/pngimages/924/868/png-clipart-ph-colorings-female-anime-character-wearing-green-dress.png' width='100' height='100' class='img-thumbnail mb-2' alt='Anime Style 3'>
      </div>
    </div>`;
  
    document.querySelector('.row.row-cols-2.row-cols-md-4.g-3').insertAdjacentHTML('beforeend', newStyles);
  }
  </script>
  
  <style scoped>
  .container {
    padding-top: 20px;
  }
  .btn-outline-primary {
    margin-right: 5px;
  }
  .img-thumbnail {
    cursor: pointer;
    transition: transform 0.2s;
  }
  .img-thumbnail:hover {
    transform: scale(1.1);
  }
  </style>