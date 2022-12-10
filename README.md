1. не понимаю когда нужно ставить "justifai content center" и "margin left right auto"
2. как сделат что б модалка не уменьшалась меньше 320px

<!-- mob conteiner -->
          <div class="header__mob-conteiner" >
            <button class="modal__button-close modal__button-close--big" >
              <svg class="close_modal__svg" width="18.67" height="18.67">
                <use href="./images/symbol-defs.svg#icon-close"></use>
              </svg>
            </button>

            <button class="icon-menu" type="button">
            <svg class="icon-menu__svg" width="24" height="16">
              <use href="./images/symbol-defs.svg#icon-menu"></use>
            </svg>
          </button>

           .header-menu {
    border-color: transparent;
    background-color: transparent;
    cursor: pointer;
    padding-top: 16px;
    padding-bottom: 16px;
    margin-left: auto;
  }
