# Smart Market backend

---

<div align="center">
  <img src="./static/app_icon.png" style="border-radius: 10px;" />
  <span style="display:inline-block; width:40px;"></span>
  <img src="https://nestjs.com/img/logo-small.svg" width="80" alt="Nest Logo" />
  <span style="display:inline-block; width:15px;"></span>
  <img src="https://avatars.githubusercontent.com/u/20165699?s=200&v=4" width="80" alt="Nest Logo" />
  <span style="display:inline-block; width:15px;"></span>
  <img src="data:image/png;base64,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" width="80" alt="Nest Logo" />
</div>

smart market 프로젝트의 백엔드 코드를 저장하는 리파지토리입니다.

---

## 목적

- 해당 프로젝트는 작성자의 학습 겸 포트폴리오의 용도로 제작된 프로젝트입니다.
- 백엔드 프로젝트는 프로토타입과 실서비스 두 가지로 나뉩니다.
- 프로토타입은 작성자가 nestjs 프레임워크를 학습한 상태에서 쇼핑몰 모델의 기본적인 요소, nestjs 아키텍처를 병합한 형태입니다.
- 실서비스는 smart market앱과 최적화된 상태의 프로젝트로 smart market앱의 요구사항을 추가로 반형하였습니다.

## 작업기간

- 프로토타입: 2022-05-23 ~ 2025-04-11
- 실서비스: 2025-04-16 ~ 진행중

## Folder Structure

```
📦src
┣ 📂common
┃ ┣ 📂classes
┃ ┃ ┗ 📜env-data.ts
┃ ┣ 📂config
┃ ┃ ┣ 📂cookie-key-configs
┃ ┃ ┃ ┣ 📂cart-cookie-keys
┃ ┃ ┃ ┃ ┗ 📜cart-cookie.key.ts
┃ ┃ ┃ ┗ 📂media-cookie-keys
┃ ┃ ┃ ┃ ┣ 📜inquiry-media-cookie.key.ts
┃ ┃ ┃ ┃ ┣ 📜product-media-cookie.key.ts
┃ ┃ ┃ ┃ ┗ 📜review-media-cookie.key.ts
┃ ┃ ┣ 📂event-configs
┃ ┃ ┃ ┗ 📜index.ts
┃ ┃ ┣ 📂repository-select-configs
┃ ┃ ┃ ┣ 📜account.select.ts
┃ ┃ ┃ ┣ 📜cart.select.ts
┃ ┃ ┃ ┣ 📜inquiry.select.ts
┃ ┃ ┃ ┣ 📜media.select.ts
┃ ┃ ┃ ┣ 📜order.select.ts
┃ ┃ ┃ ┣ 📜product.select.ts
┃ ┃ ┃ ┣ 📜review.select.ts
┃ ┃ ┃ ┗ 📜user.select.ts
┃ ┃ ┗ 📂static-media-configs
┃ ┃ ┃ ┗ 📜index.ts
┃ ┣ 📂decorators
┃ ┃ ┣ 📜cookies-filter.ts
┃ ┃ ┣ 📜general.decoration.ts
┃ ┃ ┣ 📜get-basic-auth.decorator.ts
┃ ┃ ┣ 📜get.jwt.decorator.ts
┃ ┃ ┣ 📜implemented.decoration.ts
┃ ┃ ┣ 📜media-cookies-parser.decorator.ts
┃ ┃ ┗ 📜transaction.decorator.ts
┃ ┣ 📂docs
┃ ┃ ┣ 📜align.swagger.ts
┃ ┃ ┣ 📜internal-server-error.swagger.ts
┃ ┃ ┣ 📜typeorm-error.swagger.ts
┃ ┃ ┗ 📜uuid-param.swagger.ts
┃ ┣ 📂entities
┃ ┃ ┣ 📜child.entity.ts
┃ ┃ ┣ 📜common.entity.ts
┃ ┃ ┣ 📜date.entity.ts
┃ ┃ ┣ 📜media.entity.ts
┃ ┃ ┗ 📜post.entity.ts
┃ ┣ 📂errors
┃ ┃ ┣ 📜jwt.error.ts
┃ ┃ ┣ 📜jwt.exception.ts
┃ ┃ ┣ 📜library.error.ts
┃ ┃ ┣ 📜library.exception.ts
┃ ┃ ┣ 📜typeorm.exception.ts
┃ ┃ ┗ 📜validation.exception.ts
┃ ┣ 📂filters
┃ ┃ ┣ 📜http-exception.filter.ts
┃ ┃ ┣ 📜jwt-exception.filter.ts
┃ ┃ ┣ 📜library-exception.filter.ts
┃ ┃ ┣ 📜typeorm-exception.filter.ts
┃ ┃ ┗ 📜validation-exception.filter.ts
┃ ┣ 📂functions
┃ ┃ ┣ 📜callbacks.ts
┃ ┃ ┣ 📜logger.factory.ts
┃ ┃ ┗ 📜none-enum.ts
┃ ┣ 📂guards
┃ ┃ ┗ 📂authenticate
┃ ┃ ┃ ┣ 📜is-admin.guard.ts
┃ ┃ ┃ ┣ 📜is-client.guard.ts
┃ ┃ ┃ ┣ 📜is-login.guard.ts
┃ ┃ ┃ ┣ 📜is-not-login.guard.ts
┃ ┃ ┃ ┣ 📜is-refresh-token-available.guard.ts
┃ ┃ ┃ ┗ 📜logout.guard.ts
┃ ┣ 📂interceptors
┃ ┃ ┣ 📂general
┃ ┃ ┃ ┣ 📜json-clear-cookie.interceptor.ts
┃ ┃ ┃ ┣ 📜json-clear-cookies.interceptor.ts
┃ ┃ ┃ ┣ 📜json-general.interceptor.ts
┃ ┃ ┃ ┣ 📜json-send-cookie.interceptor.ts
┃ ┃ ┃ ┣ 📜json-send-cookies.interceptor.ts
┃ ┃ ┃ ┣ 📜login.interceptor.ts
┃ ┃ ┃ ┣ 📜logout.interceptor.ts
┃ ┃ ┃ ┗ 📜refresh-token.interceptor.ts
┃ ┃ ┗ 📂interface
┃ ┃ ┃ ┣ 📜json-clear-cookie.interface.ts
┃ ┃ ┃ ┣ 📜json-clear-cookies.interface.ts
┃ ┃ ┃ ┣ 📜json-general-interface.ts
┃ ┃ ┃ ┣ 📜json-send-cookie-param.interface.ts
┃ ┃ ┃ ┣ 📜json-send-cookies-param.interface.ts
┃ ┃ ┃ ┣ 📜json-send-cookies.interface.ts
┃ ┃ ┃ ┣ 📜login.interface.ts
┃ ┃ ┃ ┣ 📜logout.interface.ts
┃ ┃ ┃ ┣ 📜refresh-token.interface.ts
┃ ┃ ┃ ┗ 📜verify-data.dto.ts
┃ ┣ 📂interfaces
┃ ┃ ┣ 📂initializer
┃ ┃ ┃ ┗ 📜transactional.ts
┃ ┃ ┗ 📂search
┃ ┃ ┃ ┣ 📜search.repository.ts
┃ ┃ ┃ ┗ 📜searcher.ts
┃ ┣ 📂lib
┃ ┃ ┣ 📂database
┃ ┃ ┃ ┣ 📜cache-manager-redis-store.ts
┃ ┃ ┃ ┣ 📜redis-adapt.module.ts.module.ts
┃ ┃ ┃ ┗ 📜typeorm-adapt.module.ts
┃ ┃ ┣ 📂email
┃ ┃ ┃ ┣ 📜email-sender.library.ts
┃ ┃ ┃ ┗ 📜mailer-adapt.module.ts
┃ ┃ ┣ 📂env
┃ ┃ ┃ ┗ 📜dotenv-adapt.module.ts
┃ ┃ ┣ 📂event
┃ ┃ ┃ ┗ 📜event-adapt.module.ts
┃ ┃ ┣ 📂handler
┃ ┃ ┃ ┗ 📜transaction.handler.ts
┃ ┃ ┣ 📂jwt
┃ ┃ ┃ ┣ 📜jwt-error-handler.library.ts
┃ ┃ ┃ ┗ 📜jwt-exception-followup.ts
┃ ┃ ┣ 📂logger
┃ ┃ ┃ ┣ 📜media-logger.library.ts
┃ ┃ ┃ ┗ 📜time-logger.library.ts
┃ ┃ ┣ 📂media
┃ ┃ ┃ ┗ 📜multer-adapt.module.ts
┃ ┃ ┣ 📂security
┃ ┃ ┃ ┣ 📜security.library.ts
┃ ┃ ┃ ┗ 📜validate-token.library.ts
┃ ┃ ┣ 📂util
┃ ┃ ┃ ┣ 📜catch-callback-factory.library.ts
┃ ┃ ┃ ┗ 📜validate.library.ts
┃ ┃ ┗ 📜library.module.ts
┃ ┣ 📂middlewares
┃ ┃ ┗ 📜response-logger.middleware.ts
┃ ┣ 📂security
┃ ┃ ┗ 📜env-keys.ts
┃ ┗ 📂types
┃ ┃ ┣ 📜align-by.type.ts
┃ ┃ ┣ 📜express.d.ts
┃ ┃ ┗ 📜media-cookies.ts
┣ 📂deprecated
┃ ┣ 📜cookie.library.ts
┃ ┣ 📜find-email-logic.ts
┃ ┣ 📜find-product-with-id-logic.ts
┃ ┣ 📜jwt.strategy.ts
┃ ┣ 📜promise-exception.filter.ts
┃ ┣ 📜promise-handle.exception.ts
┃ ┣ 📜promise.library.ts
┃ ┣ 📜promises-processor.ts
┃ ┣ 📜register-user-logic.ts
┃ ┗ 📜user-insert.repository.ts
┣ 📂model
┃ ┣ 📂account
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┗ 📜account-v1.controller.ts
┃ ┃ ┣ 📂dtos
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜account-body.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-account.dto.ts
┃ ┃ ┃ ┃ ┣ 📜delete-account.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-accounts.dto.ts
┃ ┃ ┃ ┃ ┗ 📜money-transaction.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜account-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┣ 📜deposit-result.dto.ts
┃ ┃ ┃ ┃ ┗ 📜withdraw-result.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┗ 📜account.entity.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜account-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜account-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜account-transaction.executor.ts
┃ ┃ ┃ ┃ ┣ 📜account-transaction.initializer.ts
┃ ┃ ┃ ┃ ┗ 📜account-transaction.searcher.ts
┃ ┃ ┃ ┣ 📜account.searcher.ts
┃ ┃ ┃ ┗ 📜account.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┣ 📂exist
┃ ┃ ┃ ┃ ┗ 📜account-id-validate.pipe.ts
┃ ┃ ┃ ┗ 📂none-exist
┃ ┃ ┃ ┃ ┗ 📜account-number-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜account-search.repository.ts
┃ ┃ ┃ ┣ 📜account-update.repository.ts
┃ ┃ ┃ ┗ 📜account-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜account.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┗ 📜bank.category.type.ts
┃ ┃ ┗ 📜account.module.ts
┃ ┣ 📂auth
┃ ┃ ┣ 📂docs
┃ ┃ ┃ ┣ 📜is-not-admin.swagger.ts
┃ ┃ ┃ ┣ 📜is-not-client.swagger.ts
┃ ┃ ┃ ┗ 📜jwt-auth.swagger.ts
┃ ┃ ┣ 📂jwt
┃ ┃ ┃ ┣ 📜jwt-access-token-payload.interface.ts
┃ ┃ ┃ ┣ 📜jwt-payload.interface.ts
┃ ┃ ┃ ┣ 📜jwt-refresh-token-payload.interface.ts
┃ ┃ ┃ ┗ 📜jwt-what-token.type.ts
┃ ┃ ┗ 📜auth.module.ts
┃ ┣ 📂cart
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┗ 📜cart-v1-client.controller.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜cart-body.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-cart.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-carts.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-cart.dto.ts
┃ ┃ ┃ ┃ ┗ 📜validate-product-amount.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜carts-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┗ 📜carts-response.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┗ 📜cart.entity.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📜cart.searcher.ts
┃ ┃ ┃ ┗ 📜cart.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┗ 📜cart-id-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜cart-search.repository.ts
┃ ┃ ┃ ┣ 📜cart-update.repository.ts
┃ ┃ ┃ ┗ 📜cart-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜cart.service.ts
┃ ┃ ┗ 📜cart.module.ts
┃ ┣ 📂inquiry
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┣ 📜inquiry-v1-admin.controller.ts
┃ ┃ ┃ ┗ 📜inquiry-v1-client.controller.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂inquiry-request
┃ ┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┃ ┣ 📜create-inquiry-request.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜find-all-inquiry-requests.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-request-body.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜insert-inquiry-request-image.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜insert-inquiry-request-video.dto.ts
┃ ┃ ┃ ┃ ┃ ┗ 📜search-create-inquiry-request.dto.ts
┃ ┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-request-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-request-detail-raw.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-request-from-admin-product-raw.dto.ts
┃ ┃ ┃ ┃ ┃ ┗ 📜send-mail-to-admin-about-inquiry-request.dto.ts
┃ ┃ ┃ ┗ 📂inquiry-response
┃ ┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┃ ┣ 📜create-inquiry-response.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜find-all-inquiry-responses.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-response-body.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜insert-inquiry-response-image.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜insert-inquiry-response-video.dto.ts
┃ ┃ ┃ ┃ ┃ ┗ 📜search-create-inquiry-response.dto.ts
┃ ┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-response-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┃ ┣ 📜inquiry-response-detail-raw.dto.ts
┃ ┃ ┃ ┃ ┃ ┗ 📜send-mail-to-client-about-inquiry-response.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┣ 📜inquiry-request.entity.ts
┃ ┃ ┃ ┗ 📜inquiry-response.entity.ts
┃ ┃ ┣ 📂interceptor
┃ ┃ ┃ ┣ 📜inquiry-admin-event.interceptor.ts
┃ ┃ ┃ ┗ 📜inquiry-client-event.interceptor.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜inquiry-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-transaction.executor.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-transaction.initializer.ts
┃ ┃ ┃ ┃ ┗ 📜inquiry-transaction.searcher.ts
┃ ┃ ┃ ┣ 📜inquiry-event-map.setter.ts
┃ ┃ ┃ ┣ 📜inquiry-request.searcher.ts
┃ ┃ ┃ ┣ 📜inquiry-response.searcher.ts
┃ ┃ ┃ ┗ 📜inquiry.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┗ 📂exist
┃ ┃ ┃ ┃ ┣ 📜inquiry-request-id-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-requester-id-validate.pipe.ts
┃ ┃ ┃ ┃ ┗ 📜inquiry-response-id-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜inquiry-request-search.repository.ts
┃ ┃ ┃ ┣ 📜inquiry-response-search.repository.ts
┃ ┃ ┃ ┣ 📜inquiry-update.repository.ts
┃ ┃ ┃ ┗ 📜inquiry-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜inquiry.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┗ 📜inquiry-option.type.ts
┃ ┃ ┗ 📜inquiry.module.ts
┃ ┣ 📂media
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┣ 📜media-v1-admin.controller.ts
┃ ┃ ┃ ┗ 📜media-v1-client.controller.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜delete-media-files.dto.ts
┃ ┃ ┃ ┃ ┣ 📜media-cookie.dto.ts
┃ ┃ ┃ ┃ ┗ 📜upload-media.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜media-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┗ 📜set-delete-media-files.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┣ 📜inquiry-request-image.entity.ts
┃ ┃ ┃ ┣ 📜inquiry-request-video.entity.ts
┃ ┃ ┃ ┣ 📜inquiry-response-image.entity.ts
┃ ┃ ┃ ┣ 📜inquiry-response-video.entity.ts
┃ ┃ ┃ ┣ 📜product-image.entity.ts
┃ ┃ ┃ ┣ 📜review-image.entity.ts
┃ ┃ ┃ ┗ 📜review-video.entity.ts
┃ ┃ ┣ 📂interceptor
┃ ┃ ┃ ┣ 📜delete-inquiry-request-media.interceptor.ts
┃ ┃ ┃ ┣ 📜delete-inquiry-response-media.interceptor.ts
┃ ┃ ┃ ┣ 📜delete-product-media.interceptor.ts
┃ ┃ ┃ ┗ 📜delete-review-media.interceptor.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📜inquiry-request-image.searcher.ts
┃ ┃ ┃ ┣ 📜inquiry-request-video.searcher.ts
┃ ┃ ┃ ┣ 📜inquiry-response-image.searcher.ts
┃ ┃ ┃ ┣ 📜inquiry-response-video.searcher.ts
┃ ┃ ┃ ┣ 📜media-event-map.setter.ts
┃ ┃ ┃ ┣ 📜media-file.eraser.ts
┃ ┃ ┃ ┣ 📜media.utils.ts
┃ ┃ ┃ ┣ 📜media.validator.ts
┃ ┃ ┃ ┣ 📜product-image.searcher.ts
┃ ┃ ┃ ┣ 📜review-image.searcher.ts
┃ ┃ ┃ ┗ 📜review-video.searcher.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┗ 📂exist
┃ ┃ ┃ ┃ ┣ 📜inquiry-request-image-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-request-video-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-response-image-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜inquiry-response-video-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜product-images-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜review-image-validate.pipe.ts
┃ ┃ ┃ ┃ ┗ 📜review-video-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜inquiry-request-image-search.repository.ts
┃ ┃ ┃ ┣ 📜inquiry-request-video-search.repository.ts
┃ ┃ ┃ ┣ 📜inquiry-response-image-search.repository.ts
┃ ┃ ┃ ┣ 📜inquiry-response-video-search.repository.ts
┃ ┃ ┃ ┣ 📜media-update.repository.ts
┃ ┃ ┃ ┣ 📜product-image-search.repository.ts
┃ ┃ ┃ ┣ 📜review-image-search.repository.ts
┃ ┃ ┃ ┗ 📜review-video-search.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜media.service.ts
┃ ┃ ┗ 📜media.module.ts
┃ ┣ 📂order
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┗ 📜order-v1-client.contoller.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜create-order.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-payment.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-payments.dto.ts
┃ ┃ ┃ ┃ ┣ 📜decrease-product-stock.dto.ts
┃ ┃ ┃ ┃ ┣ 📜deposit-admin-balance.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-orders.dto.ts
┃ ┃ ┃ ┃ ┣ 📜order-body.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-create-order.dto.ts
┃ ┃ ┃ ┃ ┗ 📜withdraw-client-balance.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┗ 📜order-basic-raw.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┣ 📜order.entity.ts
┃ ┃ ┃ ┗ 📜payment.entity.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜order-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜order-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜order-transaction.executor.ts
┃ ┃ ┃ ┃ ┣ 📜order-transaction.initializer.ts
┃ ┃ ┃ ┃ ┗ 📜order-transaction.searcher.ts
┃ ┃ ┃ ┗ 📜order.searcher.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜order-search.repository.ts
┃ ┃ ┃ ┗ 📜order-update.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜order.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┣ 📜delivery-option.type.ts
┃ ┃ ┃ ┣ 📜product-quantity.type.ts
┃ ┃ ┃ ┗ 📜transaction-status.type.ts
┃ ┃ ┗ 📜order.module.ts
┃ ┣ 📂product
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┣ 📜product-v1-admin.controller.ts
┃ ┃ ┃ ┃ ┗ 📜product-v1.controller.ts
┃ ┃ ┣ 📂docs
┃ ┃ ┃ ┣ 📂product-v1-admin-controller
┃ ┃ ┃ ┃ ┗ 📜create-product.swagger.ts
┃ ┃ ┃ ┗ 📂product-v1-controller
┃ ┃ ┃ ┃ ┣ 📜find-all-products-from-latest.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-products-from-oldest.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-products.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜find-detail-product.swagger.ts
┃ ┃ ┃ ┃ ┗ 📜find-product-with-name.swagger.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜access_product_name.dto.ts
┃ ┃ ┃ ┃ ┣ 📜change-product-image.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-product.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-products.dto.ts
┃ ┃ ┃ ┃ ┣ 📜insert-product-image.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-category.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-description.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-image.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-name.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-origin.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-price.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product-stock.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-product.dto.ts
┃ ┃ ┃ ┃ ┣ 📜product-body.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-create-product.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-modify-product-image.dto.ts
┃ ┃ ┃ ┃ ┗ 📜search-modify-product.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜product-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┗ 📜product-detail-raw.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┗ 📜product.entity.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜product-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜product-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜product-transaction.executor.ts
┃ ┃ ┃ ┃ ┣ 📜product-transaction.initializer.ts
┃ ┃ ┃ ┃ ┗ 📜product-transaction.searcher.ts
┃ ┃ ┃ ┣ 📜product.searcher.ts
┃ ┃ ┃ ┗ 📜product.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┣ 📂exist
┃ ┃ ┃ ┃ ┗ 📜product-id-validate.pipe.ts
┃ ┃ ┃ ┗ 📂none-exist
┃ ┃ ┃ ┃ ┗ 📜operate-product-validation.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜product-search.repository.ts
┃ ┃ ┃ ┣ 📜product-update.repository.ts
┃ ┃ ┃ ┗ 📜product-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜product.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┗ 📜product-category.type.ts
┃ ┃ ┗ 📜product.module.ts
┃ ┣ 📂review
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┣ 📜review-v1-admin.controller.ts
┃ ┃ ┃ ┃ ┗ 📜review-v1-client.controller.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜change-review-image.dto.ts
┃ ┃ ┃ ┃ ┣ 📜change-review-video.dto.ts
┃ ┃ ┃ ┃ ┣ 📜create-review.dto.ts
┃ ┃ ┃ ┃ ┣ 📜delete-review.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-reviews.dto.ts
┃ ┃ ┃ ┃ ┣ 📜insert-review-image.dto.ts
┃ ┃ ┃ ┃ ┣ 📜insert-review-video.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-review.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-star-rate.dto.ts
┃ ┃ ┃ ┃ ┣ 📜review-body.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-create-review.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-delete-review.dto.ts
┃ ┃ ┃ ┃ ┣ 📜search-modify-review.dto.ts
┃ ┃ ┃ ┃ ┗ 📜star-rating.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜review-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┣ 📜review-detail-raw.dto.ts
┃ ┃ ┃ ┃ ┗ 📜review-from-product-raw.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┣ 📜review.entity.ts
┃ ┃ ┃ ┗ 📜star-rate.entity.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜review-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜review-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜review-transaction.executor.ts
┃ ┃ ┃ ┃ ┣ 📜review-transaction.initializer.ts
┃ ┃ ┃ ┃ ┗ 📜review-transaction.searcher.ts
┃ ┃ ┃ ┣ 📜review.searcher.ts
┃ ┃ ┃ ┣ 📜review.utils.ts
┃ ┃ ┃ ┗ 📜review.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┗ 📂exist
┃ ┃ ┃ ┃ ┗ 📜review-id-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜review-search.repository.ts
┃ ┃ ┃ ┣ 📜review-update.repository.ts
┃ ┃ ┃ ┗ 📜review-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜review.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┗ 📜star-rate-score.type.ts
┃ ┃ ┗ 📜review.module.ts
┃ ┗ 📂user
┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┗ 📂v1
┃ ┃ ┃ ┃ ┣ 📜user-v1-admin.controller.ts
┃ ┃ ┃ ┃ ┗ 📜user-v1.controller.ts
┃ ┃ ┣ 📂docs
┃ ┃ ┃ ┣ 📂user-v1-admin-controller
┃ ┃ ┃ ┃ ┣ 📜find-all-users.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜find-detail-client-user.swagger.ts
┃ ┃ ┃ ┃ ┗ 📜kick-user.swagger.ts
┃ ┃ ┃ ┗ 📂user-v1-controller
┃ ┃ ┃ ┃ ┣ 📜find-forgotten-email.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜login.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜logout.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-address.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-email.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-nick-name.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-password.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-phone-number.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜profile.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜refresh-token.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜register.swagger.ts
┃ ┃ ┃ ┃ ┣ 📜reset-password.swagger.ts
┃ ┃ ┃ ┃ ┗ 📜secession.swagger.ts
┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┣ 📜basic-auth.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-all-users.dto.ts
┃ ┃ ┃ ┃ ┣ 📜find-email.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-address.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-email.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-nickname.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-password.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user-phonenumber.dto.ts
┃ ┃ ┃ ┃ ┣ 📜modify-user.dto.ts
┃ ┃ ┃ ┃ ┗ 📜register-user.dto.ts
┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┣ 📜client-user-raw.dto.ts
┃ ┃ ┃ ┃ ┣ 📜send-mail-to-client-about-register.dto.ts
┃ ┃ ┃ ┃ ┣ 📜user-basic-raw.dto.ts
┃ ┃ ┃ ┃ ┗ 📜user-profile-raw.dto.ts
┃ ┃ ┣ 📂entities
┃ ┃ ┃ ┣ 📜admin-user.entity.ts
┃ ┃ ┃ ┣ 📜client-user.entity.ts
┃ ┃ ┃ ┣ 📜user-auth.entity.ts
┃ ┃ ┃ ┣ 📜user-profile.entity.ts
┃ ┃ ┃ ┗ 📜user.entity.ts
┃ ┃ ┣ 📂interceptor
┃ ┃ ┃ ┗ 📜user-register-event.interceptor.ts
┃ ┃ ┣ 📂logic
┃ ┃ ┃ ┣ 📂transaction
┃ ┃ ┃ ┃ ┣ 📜user-repository.payload.ts
┃ ┃ ┃ ┃ ┣ 📜user-transaction.context.ts
┃ ┃ ┃ ┃ ┣ 📜user-transaction.executor.ts
┃ ┃ ┃ ┃ ┗ 📜user-transaction.initializer.ts
┃ ┃ ┃ ┣ 📜user-event-map.setter.ts
┃ ┃ ┃ ┣ 📜user.searcher.ts
┃ ┃ ┃ ┣ 📜user.security.ts
┃ ┃ ┃ ┗ 📜user.validator.ts
┃ ┃ ┣ 📂pipe
┃ ┃ ┃ ┣ 📂exist
┃ ┃ ┃ ┃ ┣ 📜client-user-id-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜find-email-validation.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜user-email-validate.pipe.ts
┃ ┃ ┃ ┃ ┗ 📜user-id-validate.pipe.ts
┃ ┃ ┃ ┗ 📂none-exist
┃ ┃ ┃ ┃ ┣ 📜user-email-validate.pipe.ts
┃ ┃ ┃ ┃ ┣ 📜user-nickname-validate.pipe.ts
┃ ┃ ┃ ┃ ┗ 📜user-phonenumber-validate.pipe.ts
┃ ┃ ┣ 📂repositories
┃ ┃ ┃ ┣ 📜user-search.repository.ts
┃ ┃ ┃ ┣ 📜user-update.repository.ts
┃ ┃ ┃ ┗ 📜user-validate.repository.ts
┃ ┃ ┣ 📂services
┃ ┃ ┃ ┗ 📜user.service.ts
┃ ┃ ┣ 📂types
┃ ┃ ┃ ┣ 📜user-gender.type.ts
┃ ┃ ┃ ┗ 📜user-role.type.ts
┃ ┃ ┗ 📜user.module.ts
┣ 📜app.controller.ts
┣ 📜app.module.ts
┗ 📜main.ts
```
