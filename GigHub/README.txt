use the latest automapper version (AutoMapper .6.0.2 as of today):

var config = new MapperConfiguration(cfg =>
              {
                  cfg.CreateMap<ApplicationUser, UserDto>();
                  cfg.CreateMap<Genre,GenreDto>();
                  cfg.CreateMap<Gig,GigDto>();
                  cfg.CreateMap<Notification, NotificationDto>();
              });
            IMapper mapper = config.CreateMapper();
            return notifications.Select(mapper.Map<Notification, NotificationDto>);


animate.css
bootstrap:popover

moment.js

bootbax.js

_underscore.js

less

postman

BootStrap Events


