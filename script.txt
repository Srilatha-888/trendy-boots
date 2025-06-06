
    const btn  = document.getElementById('dropdownBtn');
    const wrap = btn.parentElement;
    btn.addEventListener('click', e => {
      e.stopPropagation();
      wrap.classList.toggle('open');
    });
    document.addEventListener('click', () => wrap.classList.remove('open'));
  