document.addEventListener('DOMContentLoaded', () => {
    const menuToggle = document.getElementById('menuToggle');
    const fullscreenMenu = document.getElementById('fullscreenMenu');
    const menuText = menuToggle.querySelector('.menu-text');

    // Simple open/close toggle control logic
    menuToggle.addEventListener('click', () => {
        const isOpen = fullscreenMenu.classList.toggle('active');
        document.body.classList.toggle('menu-open', isOpen);
        
        // Dynamically alter text layout matching state context
        if (isOpen) {
            menuText.textContent = 'CLOSE';
            // Switch header link color elements to dark layout inside cream menu container
            document.querySelectorAll('.brand-logo, .menu-text, .hamburger-icon span').forEach(el => {
                if(el.tagName === 'SPAN') {
                    el.style.backgroundColor = '#111111';
                } else {
                    el.style.color = '#111111';
                }
            });
        } else {
            menuText.textContent = 'MENU';
            // Revert to default navigation overlay color profiles
            document.querySelectorAll('.brand-logo, .menu-text, .hamburger-icon span').forEach(el => {
                if(el.tagName === 'SPAN') {
                    el.style.backgroundColor = '#ffffff';
                } else {
                    el.style.color = '#ffffff';
                }
            });
        }
    });

    // Auto-close menu window context safely upon interior link triggers
    const menuItems = document.querySelectorAll('.menu-item');
    menuItems.forEach(item => {
        item.addEventListener('click', () => {
            fullscreenMenu.classList.remove('active');
            document.body.classList.remove('menu-open');
            menuText.textContent = 'MENU';
            document.querySelectorAll('.brand-logo, .menu-text, .hamburger-icon span').forEach(el => {
                if(el.tagName === 'SPAN') {
                    el.style.backgroundColor = '#ffffff';
                } else {
                    el.style.color = '#ffffff';
                }
            });
        });
    });
});
