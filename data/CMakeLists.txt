
# Install the scope ini file
install(
  FILES "com.ubuntu.developer.liu-xiao-guo.chinaweather_chinaweather.ini"
  DESTINATION ${SCOPE_INSTALL_DIR}
)

# Install the scope images
install(
  FILES
    "icon.png"
    "logo.png"
    "screenshot.png"
  DESTINATION
    "${SCOPE_INSTALL_DIR}"
)

