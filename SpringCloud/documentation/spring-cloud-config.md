

##### 1. [快速起步](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_quick_start)
##### 2. [Config Server](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_spring_cloud_config_server)
- 2.1 [配置仓库](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_environment_repository)
    + 2.1.1 [Git后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_git_backend)
        - [跳过SSL证书认证](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_skipping_ssl_certificate_validation)
        - [设置HTTP连接超时](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_setting_http_connection_timeout)
        - [Git URI中的占位符](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_placeholders_in_git_uri)
        - [模式匹配和多仓库](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_pattern_matching_and_multiple_repositories)
        - [认证](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_authentication)
        - [属性配置Git SSH](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_git_ssh_configuration_using_properties)
        - [Git 搜索路径的占位符](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_placeholders_in_git_search_paths)
        - [强制从配置仓库中pull](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_force_pull_in_git_repositories)
        - [在Git仓库中删除未跟踪分支](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_deleting_untracked_branches_in_git_repositories)
        - [Git的刷新速率](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_git_refresh_rate)
    + 2.1.2 [文件系统后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_file_system_backend)
    + 2.1.3 [Vault后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#vault-backend)
    + 2.1.4 [通过代理访问后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_accessing_backends_through_a_proxy)
    + 2.1.5 [所有应用共享配置](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_sharing_configuration_with_all_applications)
    + 2.1.6 [JDBC后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_jdbc_backend)
    + 2.1.7 [Redis后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_redis_backend)
    + 2.1.8 [暴露多个配置仓库](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#composite-environment-repositories)
- 2.2 [健康指标](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_health_indicator)
- 2.3 [安全](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_security)
- 2.4 [加密与解密](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_encryption_and_decryption)
- 2.5 [Key管理](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_key_management)
- 2.6 [创建一个Key Store并测试](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_creating_a_key_store_for_testing)
- 2.7 [使用Multiple Key和Key Rotation](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_using_multiple_keys_and_key_rotation)
- 2.8 [加密服务属性](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_serving_encrypted_properties)
##### 3. [可选的配置文件格式](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_serving_alternative_formats)
##### 4. [纯文本的配置文件](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_serving_plain_text)
- 4.1 [Git,SVN和本地的后端](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#spring-cloud-config-serving-plain-text-git-svn-native-backends)
- 4.2 [纯文本解密](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_decrypting_plain_text)
##### 5. [嵌入式Config Server](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_embedding_the_config_server)
##### 6. [推送通知和Spring Cloud Bus](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_push_notifications_and_spring_cloud_bus)
##### 7. [Spring Cloud Config Client](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_spring_cloud_config_client)
- 7.1 [Spring Boot Config Data Import](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#config-data-import)
- 7.2 [起步配置](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#config-first-bootstrap)
- 7.3 [注册服务](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#discovery-first-bootstrap)
- 7.4 [配置客户端Fail Fast](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#config-client-fail-fast)
- 7.5 [Config客户端Retry](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#config-client-retry)
- 7.6 [定位远程配置资源](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_locating_remote_configuration_resources)
- 7.7 [为Config Server配置多个Url](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_specifying_multiple_urls_for_the_config_server)
- 7.8 [配置超时](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_configuring_timeouts)
- 7.9 [安全](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_security_2)